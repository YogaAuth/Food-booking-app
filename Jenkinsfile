pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/YogaAuth/Food-booking-app.git'
            }
        }

        stage('Verify Files') {
            steps {
                echo 'Food Booking App Pipeline Started'
            }
        }

    }
}