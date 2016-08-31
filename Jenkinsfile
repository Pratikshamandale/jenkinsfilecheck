
node('master')
{

sh "echo hello > file"
sh "echo hello >> file"

//File file = new File("/tmp/author")
def lines = readFile("/tmp/author").readLines()

println lines[0]



}  
