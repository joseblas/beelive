stage ("Build") {
    node (){
        echo 'building the artifact'
        sleep 5
            }        
          }    

stage ("QA Test") {
   node () {
        echo "QA tests..."
        sleep 5
    } 
  }

stage ("Deploy") {
   node () {
        input 'Deploy on load test environment?'
        echo "deploying to test environment."
        sleep 5
  } 
}
