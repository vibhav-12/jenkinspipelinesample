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
	bat 'mvn clean compile'
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
	bat 'mvn test'
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
	bat 'mvn deploy'
	echo "abcd"
	   }
	
   }
} 




}



}
