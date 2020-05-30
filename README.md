# Git based Social Networking Script

A very simple social networking application based on git. Users can create local or remote networks (git repositories), 
post and push their comments to the repositories and like or follow fellow members.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
This script is intended to be used for educational purposes is and not tested for production.

### Prerequisites

Git is required to be installed in the local computer.

### Installing

Get a copy of the script by cloning the [edx]( https://github.com/palexandri/edx.git) repository.

#git clone https://github.com/palexandri/edx.git

Change to edx directory.

#cd edx

Execute sn to get a list of available commands.

#./sn

The script will create a personalised json file for every network you join holding the total number
of posts, the people that you follow and the likes that you have made. It will also allow you to 
setup git on first run.

## Examples

To create a new network named cooking, join it and post somthing you need to execute the following commands:

#./sn create cooking
#./sn join cooking
#./sn post

To follow a member's posts you need to execute sn follow and supply the member'e email:

#./sn follow palexandri@gmail.com

Each time the member pushes his/hers posts to the network, you will receive an email to your git supplied email address. 

## Authors

* **Petros Alexandridis** - *Initial work* - [palexandri]( https://github.com/palexandri)

## License

This project is licensed under the GPLv3 License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Dr Diomidis Spinellis



