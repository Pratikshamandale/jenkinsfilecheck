
def op = []
node('master')
{

sh "echo hello > file"
sh "echo hello2 >> file"

//File file = new File("/tmp/author")
def lines = readFile("file")


println "-----------------------"
println lines

lines.tokenize('\n')

println lines[0]

//sh "op=`ls`"

//println op

//def lines="git log --after='2016-08-30' | grep Author | cut -d'<' -f2|cut -d'>' -f1".execute()


//println lines[0]



}  
