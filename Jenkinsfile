node{
      stage('Clone') {
          checkout scm
      }
      stage('install_mariadb') {
	sh "ansible-playbook -i inventaire playbook.yml"
      }
}
