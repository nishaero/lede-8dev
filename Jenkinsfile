pipeline{
agent any
stages{
stage("compile"){
  steps{
  script{
   sh "make PROFILE=8devices_Carambola2 -j6 V=sc" 
  }
    }
}
}
}
