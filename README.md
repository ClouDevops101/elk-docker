
<a href="http://bitly.com/2grT54q"><img src="https://cdn.codementor.io/badges/i_am_a_codementor_dark.svg" alt="I am a codementor" style="max-width:100%"/></a><a href="http://bitly.com/2grT54q"><img src="https://www.elastic.co/fr/assets/blt9a26f88bfbd20eb5/icon-elasticsearch-bb.svg" height="50"> 
 [![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WX4EKLLLV49WG)

# Elasticsearch, Logstash, Kibana (ELK) Docker image



Description : . 

HOW It WORKS
================



### Twitter Keyword tracking
You'll need to add your secure Oauth twitter account in order to make it happen.
```
twitter {
       consumer_key => "XXXXXXXXXXXXXXXXX"
       keywords => ["DevOps","BigData","IoT"]
       consumer_secret => "XXXXXXXXXXXXXXXXXXX"
       oauth_token => "XXXXXXXXXXXXXXXXXXXXXXXXXX"
       oauth_token_secret => "XXXXXXXXXXXXXXXXXXXXXXXXXX"
       full_tweet => true
       ignore_retweets => true
       rate_limit_reset_in => 600
 }
}
```

