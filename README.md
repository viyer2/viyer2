Hi I am Venky Ananthanarayana.

Here is my attempt at solving the problem given to me.
I had fun solving  this problem

I used Perl to solve this problem.
My solution mimicks an Index to achieve speed.

I have used some perl modules that are a not a part of the standard distribution
please make sure you install them before uyou begin. These modules can be installed from cpan.

They are
1. JSON
2. Log::Log4perl
3. Term::Prompt
4. Try::Tiny
5. YAML

The application requires that a directory conatinging the JSON files to be used for processing is either supplied
via the configuration file or there is a directory called "inputFiles" at the same level as the bin directory or this file.

I have assumed that the Organization_id is the key that relates all the entities together.

My Current test case coverage stands at

------------------------ ------ ------ ------ ------ ------ ------
File                       stmt   bran   cond    sub   time  total
------------------------ ------ ------ ------ ------ ------ ------
modules/App.pm             82.9    n/a    n/a   73.3    0.0   80.6
modules/ConfigReader.pm   100.0   83.3    n/a  100.0    0.6   98.2
modules/Index.pm          100.0   81.2    n/a  100.0   86.7   97.4
modules/MyLogger.pm       100.0   50.0    n/a  100.0    1.0   90.9
modules/UserInterFace.pm   69.1   72.2    n/a   78.5    0.2   70.3
t/TestCases.t              95.0   50.0    n/a   76.1   11.4   90.7
Total                      89.3   67.7    n/a   83.5  100.0   86.8
------------------------ ------ ------ ------ ------ ------ ------

For userInterface I have focused on getting coverage for the main subroutines and haven't written test cases for the UI genertation.
The Term::Prompt module provides a lot of validation and makes sure that only valid optins are passed. 




It is next to impossible to offend me. Therefore may I please request "Please be as critical or ruthless as you can be during the code review process.". 

Please share your valuable comments and feedback on viyer2@gmail.com. If there is an oppurtunity to improve and I can do something better please let me know. I take feedback very positively and will strive to improve. 




Name:Venky Ananthanarayana
email: viyer2@gmail.com


