pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        neoloadRun executable: 'C:\\Users\\john.a.q.alcoseba\\AppData\\Local\\Programs\\NeoLoad 7.4\\bin\\NeoLoadCmd.exe', project: [server: 'http://localhost:9090, User: admin, Repository: /repository_1', name: 'neoloadDemo', publishTestResult: false], scenario: '', trendGraphs: ['AvgResponseTime', 'ErrorRate']
      }
    }

  }
}