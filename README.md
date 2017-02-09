# vcsh_mr
vcsh with mr bootstrap for my config file repos

#### clone this bootstrap repo
`vcsh clone git://github.com/milkmiruku/vcsh_mr.git`

#### make symlinks from available.d to ../config.d for this system`
`cd .config/mr/available.d`

#### mr bootstrap
`mr up`
 i don't tend to use mr again
 
#### status of all repos
`vcsh st`

#### quick git add all unstaged files in all repos
`vcsh foreach add -u'

#### commit all repos with diff as comment in commit message
`vcsh commit --verbose`

#### push all repos
`vcsh push`

#### pull all repos
`vcsh pull`
