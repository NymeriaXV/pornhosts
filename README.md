# pornhosts -- a consolidated anti porn hosts file

This is an endeavour to find all porn domains and compile them into a single hosts to allow for easy blocking of porn on your local machine or on a network.

I have created this fork because @Clefspeare13 doesn't seem to maintain the list anymore as there were no changes to the list in the last 9 months. I have checked all pull requests and merged with the serious ones, growing the list by 200% from almost 5,800 to more than 17,500 porn hosts.

In order to add this to your machine, copy the  [hosts](https://raw.githubusercontent.com/NymeriaXV/pornhosts/master/0.0.0.0/hosts), and add it to your ```hosts``` file which can be found in the following locations

macOS X, iOS, Android, Linux: /etc/hosts folder.

Windows: %SystemRoot%\system32\drivers\etc\hosts folder.

Additionally, there is a new hosts file which will force Safe Search in Bing and Google, however it has not been tested yet. It can be found [here](https://raw.githubusercontent.com/NymeriaXV/pornhosts/master/0.0.0.0%20%2B%20SafeSearch%20(beta)/hosts)

I have gotten rid of the 127.0.0.1 version. You shouldn't use it unless you know what you're doing, and if you know what you're doing, you know how to write a script to convert the hosts file.

Any helpful additions are appreciated
