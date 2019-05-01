This is for FPPF-1521


CHANGES: 

	.travis.yml
		branches: only: master > FPPF-1521	
		before_install: 
			+  - curl -LO
			+  - curl -o
		after_success: \n
	
	
	Makefile
		YOUR_WEBHOOK_URL =
		ENVS := dev stg prod > dev
		# disabled sqs	
			# aws sqs send-message \ 
		# send message to Slack
			curl -X POST -H 
		# kubectl context
			kubectl config use-context 
		# kubectl apply
			while read line;
		
		## make clean
		# get context from S3, and update .kube/config
			aws s3 cp s3://
			[ -d ~/.kube ]
			KUBECONFIG=~/.kube/config
		# delete temp config
			rm -f 
	
