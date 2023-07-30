Revising my knowledge via GitCourse: https://www.youtube.com/playlist?list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb

New

- (minus sign) functionality in VSC can be achieved by "git reset HEAD file_name_to_remove_from_staging_area"
  It was always there =P
  > Changes to be committed:
  > (use "git restore --staged <file>..." to unstage)
            new file:   test-folder-to-ignore/some_unneeded_file.js
  ... No it is "restore", not reset and "git restore readme.md" did not work for me

New info:

- git add -p index.html - Partial adding. Will ask you about each part of change, whether iy should be added or not
  Did not get how it works for now. In my case. 3 batches of code in different places adding at the same time
  Update: read comments below video related to this feature. And tried to restore my changes, and commit one more time. Worked this time...
  But comments suggested to use "s" flag first, before y/n
  Yeah... Worked like a charm now. > s - split the current hunk into smaller hunks
  Was able to split my code to 3 parts and commit two of them. See screen "before" in img folder
  VSC git extension need some time to show changes after manual operations... But it worked :P Correct Results appeared after adding image
