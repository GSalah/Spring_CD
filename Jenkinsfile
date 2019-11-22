stages {
stage('clean') {
steps {
	mvn clean
}
}
stage('package') {
steps {
	mvn package

}
}
stage('create docker image') {
steps {
	mvn docker:build
}
}
}
