The env.txt file is the environment file that you should use to create a new environment where the provided notebooks can run.

conda create --name <env> --file env.txt (ubuntu)
replace <env> by name of your environment(example suit_tutorial). 
Use this command to create a new environment using the env.txt file. It will automatically download all the required packages for the notebook to work.vv

After creating the environment, use the following command to activate the environment.
        conda activate <env_name>

Now your prompt should change from base to <env_name>.

Now you are ready to use the tutorial and have fun!!
