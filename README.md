# dbhot
练习git

## 
local 与 remote 间 虽然都是git仓库，但是扮演的角色是不同的。
local push  与 local pull 在动作上都是不同的。
local 的分支会 追踪 remote 的一个分支。
* 对于push 操作 如果local没有包含remote的最新版本，或者说remote从其它local更新了新版本，那么push操作将提示失败。
* 所以在push之前，现将remte的pull merge到local的版本，然后再决定push。
