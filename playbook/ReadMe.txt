#!!!Playbook!!!

Use 'ansible-playbook' command to run play book

#!!!Create a playbook!!!

	#Ansible Playbook is created with an extension of 'yaml' expending to "yet another markup language". 

	#create a file using any text editor with yaml or yml extension

	#!!!Format!!!

	#Format of a playbook is very important. Keep caution of not making any misktake here.

	---
	 - hosts: localhost
	 	tasks:
	 	-name: Name the task here
	 			apt: #Module
	 				name: #your job
	 		-tags:
	 			tagName #tags are not necessary but it is a good habit to use them.
	 			#Tags distinguish two task and allow us to run them selectively from the same playbook.
	 		-name: Name of another task
	 			Module: #Another module
	 				name: #......


