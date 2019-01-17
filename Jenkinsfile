pipeline{
    agent any //{
        //node{
          //  label 'XXX-agent-机器'
        //    customWorkspace "${env.JOB_NAME}/${env.BUILD_NUMBER}"
      //  }
    //}
    stages{
        stage('Build'){
            bat 'dir' //如果Jenkins安装在Windows并且执行这部分代码
            sh 'pwd' //这个是Linux的执行
            print "pwd"
        }
        stage (‘Test’) {
           bat “dir” // 如果jenkins安装在windows并执行这部分代码
           print "test"
           sh “echo ${JAVA_HOME}”  //这个是Linux的执行
       }
    }
}
