# diff-test
diff練習用featureOnFeature
変更working directory用3rd
mergetool コンフリクト用(featureブランチ用)
featureOnFeature
[credential]
	helper = manager
[diff]
	tool = p4merge
[difftool "p4merge"]
	cmd = \"C:\\Program Files\\Perforce\\p4merge.exe\"
[difftool]
	trustExitCode = false
[difftool]
	prompt = false
[merge]
	tool = p4merge
[mergetool "p4merge"]
	cmd = \"C:\\Program Files\\Perforce\\p4merge.exe\" \"$BASE\" \"$LOCAL\" \"$REMOTE\" \"$MERGED\"
[mergetool]
	trustExitCode = true
[mergetool]
	prompt = true