# GeoQuizChallenge
 Added Prev Button To GeoQuiz App as Challenge From Chapter 2
 
 I copied the gitignore from your (jcallinan) gitignore file for the Geoquiz app. Just in case any important files are missing or things don't load here are a few snapshots.
 
 ![image](https://user-images.githubusercontent.com/70352456/164345859-df91df90-9dae-48ea-a09e-03c9fb30dad9.png)

![image](https://user-images.githubusercontent.com/70352456/164345880-b6514853-f212-416e-b245-679a01bb6eda.png)

![image](https://user-images.githubusercontent.com/70352456/164345933-92366524-327b-4a29-bd76-1a2796d32416.png)

Also, I had to change the ViewModelProvider Code from what is was originally as it no longer worked.
ViewModelProvider(this).get(QuizViewModel::class.java)     --New

ViewModelProvider(this).get(QuizViewModel::class.java)     --Old

Not a big change but I had to look up to see why I was getting an error with the code that I knew in the past was working fine.

