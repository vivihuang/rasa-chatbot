## chitchat
* ask_weather OR ask_howdoing OR ask_whoisit OR ask_isbot OR ask_howold OR ask_languagesbot OR ask_time OR ask_wherefrom OR ask_whoami OR handleinsult OR nicetomeeyou OR telljoke OR ask_whatismyname OR ask_whatspossible
    - action_chitchat

## deny ask_whatspossible
* ask_whatspossible
    - action_chitchat
* deny
    - utter_nohelp

## more chitchat
* greet
    - action_greet_user
* ask_weather OR ask_howdoing OR ask_whoisit OR ask_isbot OR ask_howold OR ask_languagesbot OR ask_time OR ask_wherefrom OR ask_whoami OR handleinsult OR nicetomeeyou OR telljoke OR ask_whatismyname OR ask_whatspossible
    - action_chitchat
* ask_weather OR ask_howdoing OR ask_whoisit OR ask_isbot OR ask_howold OR ask_languagesbot OR ask_time OR ask_wherefrom OR ask_whoami OR handleinsult OR nicetomeeyou OR telljoke OR ask_whatismyname OR ask_whatspossible
    - action_chitchat

## ask_whatspossible
* greet
    - action_greet_user
* ask_whatspossible
    - action_chitchat

## ask_whatspossible more
* greet
    - action_greet_user
* ask_whatspossible
    - action_chitchat
* ask_whatspossible
    - action_chitchat
