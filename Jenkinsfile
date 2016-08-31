
def op = []
node('master')
{

sh "echo hello > file"
sh "echo hello >> file"

//File file = new File("/tmp/author")
//def lines = readFile("/tmp/author").readLines()

sh "op=`ls`"

println op


//println lines[0]



}  
