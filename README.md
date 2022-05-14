# SubmoduleExploring

git submodule add https://github.com/<pjt>

Instead of doing "git clone https://github.com/<pjt>"

"git clone --recurse-submodules https://github.com/<pjt>"

Otherwise you will get only empty folders.
Alternatively if you are stubborn as me you can 

"git clone https://github.com/<pjt>
git submodule init
git submodule update"

https://git-scm.com/book/en/v2/Git-Tools-Submodules
