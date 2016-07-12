
if you are only doing a small edit, make a copy of the line(s), not the file, you are editing locally.
Then 'git pull --rebase upstream staging'
'git checkout staging'
'git pull --rebase upstream staging'
'got push origin staging -f'
git checkout your branch name
You should be set then
