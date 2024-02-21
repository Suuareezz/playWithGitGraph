        git init
 1028  git add -A
 1029  git add -A
 1030  git commit -m "Zero"
 1031  git log
 1032  git checkout -b bug-fix
 1033  git add -A
 1034  git commit -m "Three"
 1035  git add -A
 1036  git commit -m “Four"
 1037  git log
 1038  git commit -m "Four"
 1039  git checkout -b bug-fix-experimental
 1040  git log
 1041  git add -A
 1042  git commit -m "Seven"
 1043  git add -A
 1044  git commit -m "Eight"
 1045  git log –graph
 1046  git log –-graph
 1047  git log --graph
 1048  git branch
 1049  git log
 1050  git log -1
 1051  git add -A
 1052  git commit -m "Nine"
 1053  git checkout big-fix
 1054  git checkout bug-fix
 1055  git log

 1057  git commit -m "Five" // Dont commit Five, Five.1 Should be Five

 1066  git checkout main
 1067  git checkout main
 1068  git log 
 1069  git add -A
 1070  git commit -m "One"
 1071  git add -A
 1072  git commit -m "Two"
 1073  git checkout bug-fix
 1074  git log -1
 1075  git merge main
 1076  git merge main
 1077  git status
 1078  git add cmt.txt
 1079  git log -1
 1080  git commit --amend
 1081  git merge
 1082  git commit -m "Five.1 Merge main to bug-fix"
 1083  git merge
 1084  git merge main
 1085  git branch
 1086  git log
 1087  git log
 1088  git branch
 1089  git add -A
 1090  git commit -m "Six"
 1091  git checkout main
 1092  git log
 1093  git add -A
 1094  git commit -m "Ten"
 1095  git checkout bug-fix-experimental
 1096  git log
 1097  git checkout bug-fix
 1098  git log
 1099  git merge bug-fix-experimental
 1100  git merge bug-fix-experimental
 1101  git add -A
 1102  git branch
 1103  git commit -m "Eleven"
 1104  git merge bug-fix-experimental
 1105  git branch
 1106  git log
 1107  git checkout main
 1108  git log
 1109  git add -A
 1110  git commit -m "Thirteen"
 1111  git checkout bug-fix
 1112  git checkout main
 1113  git reset HEAD~
 1114  git checkout bug-fix
 1115  git log -
 1116  git log -1
 1117  git add -A
 1118  git commit -m "Twelve"
 1119  git checkout main
 1120  git merge bug-fix
 1121  git add -A
 1122  git commit -m "Thirteen"
 1123  git branch
 1124  git merge bug-fix
 1125  git branch