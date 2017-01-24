
node{
def mvnHome
stage('preparation')
{
git 'https://github.com/RameshJinagam/game-of-life.git'
mvnHome = tool 'Maven3'
}
 stage('Build') {
      // Run the maven build
     
         sh "'${mvnHome}/bin/mvn' -Dmaven.test.failure.ignore clean package"
    }
}
