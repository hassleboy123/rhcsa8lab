##### You can install everything individually below.
- [Install the Latest Version of Virtualbox]
   - Virtual Box Extension Pack

##### Once the above software is installed. Do the following if you're running the environment on Mac:
1. Create a separate `~/bin` directory and `cd` to it.  (The directory doesn't have to be ~/bin, it can be anything you want.)
2. Clone the environment repo to it with `git clone https://github.com/rdbreak/rhcsa8env.git`
3. Change to the `rhcsa8env` directory that is now in your `~/bin` directory.
4. Run `vagrant up` to deploy the environment (If the environment has a designated repo VM it will take the longest to deploy the first time only, this is because the repo system has all the packages available to the base release but will be quicker on subsequent deployments.)
