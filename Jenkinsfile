pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/22p61a05o9/demo2_rep.git'
}
}
steps('build')
{
steps(
sh'javac hello.java'
}
}
}
}
