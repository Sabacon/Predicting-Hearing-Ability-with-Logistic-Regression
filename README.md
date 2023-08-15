## Predicting-Hearing-Ability-with-Logistic-Regression

An experiment was conducted on 5000 participants to study the effects of `age` and `physical health` on hearing loss, specifically the ability to hear high pitched tones. The data displays the result of the study in which participants were evaluated and scored for physical ability and then had to take an audio test (pass/no pass) which evaluated their ability to hear high frequencies. The age of the user was also noted. 
* Features

    * age - Age of participant in years
    * physical_score - Score achieved during physical exam

* Label/Target

    * test_result - 0 if no pass, 1 if test passed

I built a `Logistic Regression` model that predicts someone's likelihood to hear the high frequency sound based solely on their features (age and physical score).
