pipeline
{
agent any
stages{
stage ('compile stage')
{
steps{
withMaven (maven :'maven-3.5.2')
{
echo 'mvn clean'
}
}
}
stage ('testing stage')
{
steps{
withMaven (maven : 'maven-3.5.2')
{
echo 'mvn test'
}
}
}
}
}
