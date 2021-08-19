node{
    for(int i=0;i<2;i++){
        stage "Stage#" + i
        print 'hello, world!'
       
        if(i==0){
            git "https://github.com/monzosingh/bankappgradle.git"
            echo "Running on Stage#0"
        }
        else{
            build "bankapp"
            echo "Running on Stage#1"
        }
    }
}
