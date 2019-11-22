# askdata-api-python-client
# Simple scenario

# Authentication
const askdataClient = askdata(
  'YourApplicationID',
  'YourSearchOnlyAPIKey' // API key
);

# Instance of the method
const agent = instantsearch({
  askdataClient
  , 'placeholder-agentId-xxxx'});

agent.channels.addToChannels(XXXUserIdXXX, )
agent.channels.addToChannels(XXXUserIdXXX, )
