stage ("Build") {
    node (){
                echo 'building the artifact'
                sleep 10
            }        }    
stage ("QA Test") {
   node () {
        echo "QA tests..."
        sleep 10
    } }
stage ("Deploy") {
   node () {
        input 'Deploy on load test environment?'
        echo "deploying to test environment."
        sleep 10
  } }
