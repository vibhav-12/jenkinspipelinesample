pipeline
{
agent any

stages
{

stage('Compile')
{
   steps
   {
	   withMaven(maven:'maven_3_5_3')
	   {
	sh 'mvn clean compile'
	echo "abcd"
	   }
	
   }
} 
stage('Testing')
{
   steps
   {
	   withMaven(maven:'maven_3_5_3')
	   {
	sh 'mvn test'
	echo "abcd"
	   }
	
   }
} 

stage('Deploy')
{
   steps
   {
	   withMaven(maven:'maven_3_5_3')
	   {
	sh 'mvn deploy'
	echo "abcd"
	   }
	
   }
} 




}



}
