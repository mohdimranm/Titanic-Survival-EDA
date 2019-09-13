# Titanic-Survival-EDA
Variable	Definition	Key <br/>
survival	Survival	0 = No, 1 = Yes <br/>
pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd<br/>
sex	Sex <br/>	
Age	Age in years	 <br/>
sibsp	# of siblings / spouses aboard the Titanic	 <br/>
parch	# of parents / children aboard the Titanic <br/>	
ticket	Ticket number	 <br/>
fare	Passenger fare	 <br/>
cabin	Cabin number	 <br/>
embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton <br/>
Variable Notes <br/>
pclass: A proxy for socio-economic status (SES) <br/>
1st = Upper <br/>
2nd = Middle <br/>
3rd = Lower <br/>

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5<br/>

sibsp: The dataset defines family relations in this way...<br/>
Sibling = brother, sister, stepbrother, stepsister<br/>
Spouse = husband, wife (mistresses and fiancés were ignored)<br/>

parch: The dataset defines family relations in this way...<br/>
Parent = mother, father<br/>
Child = daughter, son, stepdaughter, stepson<br/>
Some children travelled only with a nanny, therefore parch=0 for them.<br/>

**I performed data cleaning on the dataset and did exploratory data analysis.Further used various classifier to classify which all people survived or not.
