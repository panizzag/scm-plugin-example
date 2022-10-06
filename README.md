# Usage

## Add changes (git add ...)
`mvn scm:add -Dbasedir=${project.basedir} -Dincludes=**/pom.xml`


## Commit & push changes (git commit -m & git push ...)
`mvn -Dmessage="Commit Message" scm:checkin`