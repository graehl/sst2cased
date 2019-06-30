# sst2cased

tsv format:
[sentence number]    [-1.0 or 1.0]   [text]

Unlike the GLUE (glue_data) version of this corpus, we keep original case (not attempting to guess the 'true case' of sentence initial capitals), and movie titles are not excluded (and the labels are +-1.0, not "0" or "1"). Further, we don't follow the GLUE dev/train sentence split. Results on this corpus are thus not directly comparable to the GLUE version.
