# slackReact
I made it because I want to make simple integrations in slack for my team. So, I tried to make it more extensible possible.
It is not finished and I am thinking about some modifications.

### How to use?
There is a sample folder in the repo and there you will see some examples and how it works. 
To run the samples you will need the slack's token and a channel name (it's just working in channels, I'm working on it). Make a copy of [configuration.php.dist](/samples/configuration.php.dist) to configuration.php and fill the token and channel. 

If you do not have php 7 in your machine, build the [container](https://github.com/matheusfaustino/docker-slackReact).

### Contribute
Feel free to contribuite(PR, issue, etc...), this is my first project, like this, related with PHP and I am not perfect and I never will be, so let's learn together. 
Anything else just contact me: [@zexias](https://twitter.com/zexias)

### TODO
- [ ] Improve README (yes, I know...)
- [ ] Improve structure
- [ ] Improve channel filter
- [ ] Create tests (shame...)
- [ ] Create log file
- [ ] Create more tasks
- [ ] Publish in packagist
- [ ] Add other kind of events
- [ ] Fix double messages when it is a message with attachment 

### License
It is under the MIT license. For the full copyright and license information, please read the [LICENSE](/LICENSE) file that was distributed with this source code.
