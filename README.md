# update-pip-not-work-
when installing in the console " python-m pip install-U pip"
Collecting pip
Exception:
Traceback (most recent call last):
  File "c:\python27\lib\site-packages\pip\_internal\cli\base_command.py", line 1
43, in main
    status = self.run(options, args)
  File "c:\python27\lib\site-packages\pip\_internal\commands\install.py", line 3
18, in run
    resolver.resolve(requirement_set)
  File "c:\python27\lib\site-packages\pip\_internal\resolve.py", line 102, in re
solve
    self._resolve_one(requirement_set, req)
  File "c:\python27\lib\site-packages\pip\_internal\resolve.py", line 256, in _r
esolve_one
    abstract_dist = self._get_abstract_dist_for(req_to_install)
  File "c:\python27\lib\site-packages\pip\_internal\resolve.py", line 209, in _g
et_abstract_dist_for
    self.require_hashes
  File "c:\python27\lib\site-packages\pip\_internal\operations\prepare.py", line
 283, in prepare_linked_requirement
    progress_bar=self.progress_bar
  File "c:\python27\lib\site-packages\pip\_internal\download.py", line 836, in u
npack_url
    progress_bar=progress_bar
  File "c:\python27\lib\site-packages\pip\_internal\download.py", line 673, in u
npack_http_url
    progress_bar)
  File "c:\python27\lib\site-packages\pip\_internal\download.py", line 895, in _
download_http_url
    file_path = os.path.join(temp_dir, filename)
  File "c:\python27\lib\ntpath.py", line 85, in join
    result_path = result_path + p_path
UnicodeDecodeError: 'ascii' codec can't decode byte 0xe0 in position 7: ordinal
not in range(128)
You are using pip version 18.1, however version 19.3.1 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' comm
and.
