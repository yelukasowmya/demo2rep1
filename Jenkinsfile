pipeline
{
agent any
stages
{
stage('clone')
{
steps
{
git 'https://github.com/yelukasowmya/demo2rep1.git'
}
}
stage('build')
{
steps
{
sh 'javac file1.java'
}
}
stage('run')
{
steps
{
sh 'java file1'
}
}
}
}
