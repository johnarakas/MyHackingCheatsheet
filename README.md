# MyHackingCheatsheet
while I am studing ethical hacking I will add usefull commands and scripts
<h2>shell_spawn</h2>
python3 -c 'import pty; pty.spawn("/bin/bash")'

echo os.system('/bin/bash')

/bin/bash -i

perl —e 'exec "/bin/bash";'

perl: exec "/bin/bash";

ruby: exec "/bin/bash"

lua: os.execute('/bin/bash')
