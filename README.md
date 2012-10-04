

=Installation


cd ~/.config/sublime-text-2/Packages/

git clone https://github.com/jesperronn/sublimetext-cucumber-snippets.git

#restart sublime text



== Provides the following snippets




==fea
Feature: ${1:Feature name}
  In order to ${2:(describe main purpose)}
  As a ${3:Customer} I should be able to ${4:(describe feature acceptance)}
  
  $0

==bac 
Background: 
  Given ${1:(I go to (pagename))}
  
  $0

==sce
Scenario: ${1:Scenario name}
  Given ${2:(I go to (pagename))}
  When ${3:I fill in "xx" with "yy"}
  Then ${4:I should see "yy" within "aa"}
  
  $0
