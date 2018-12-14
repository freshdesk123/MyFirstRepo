node("spot_backend") {

   docker.image('792634465463.dkr.ecr.us-east-1.amazonaws.com/fdesk/backend_v2').inside {
stage("checkout") {

							    //Branch checkout
                  
                   sh  """#!/bin/bash
	        source /etc/profile.d/rvm.sh
	        cd /home/jenkins/
	        git clone git@github.com:freshdesk123/MyFirstRepo.git
	        echo "cloned"
	       	"""
							}

    }
 }
