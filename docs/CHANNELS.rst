============
Channels
============

Channels in CC2.0
=================

The Contact center 2.0 platform (CC20) supports 4 channels:

#. Voice
#. Chat
#. Video
#. E-mail and actions. 

Your customers use these channels to connect to the agents in the contact centers. For voice they use their own phone of course. 
For chat and video we deliver and maintain apps that are part of your ING website and Internet banking. Soon, we'll also start supporting the Mobile banking app. 
For e-mail your customers use their own e-mail client. Actions are different: These are pieces of work that the contact center take care of. And that you can route together with the conversations. 

Customer journey experts craft customer experiences in these channels. For voice this may include self service and intelligent routing of inbound calls. In chat we support integration with chat bots. And video can be integrated with self service pages where appointments are made. 

Developers and customer journey experts create routing patterns for all 4 channels. In these patterns you set priorities and create work streams that fit the way of work of the contact centers. These are also reflected on the CC20 dashboards. And become part of the events recorded in the ING Datalake and the events stored in TeleOpti for planning. 

Agents benefit from the Omnichannel toolbar that allows them to handle their conversations in one app. Of course they too can use dashboards and planning. As can supervisors and team leaders. 

Voice channel
=============

The voice channel enables ING customers to reach our bank using their own phone. And of course, the channel is also available to agents, so they can reach out to customers.

The voice channel is powered by the Twilio cloud service that operates in 65 `countries
<https://www.twilio.com/voice/coverage/>`_.
And including the 14 countries in which ING delivers retail banking. 

Voice customer journey's
-------------------------
Since the Twilio solution consists of building blocks, many different customer journeys are possible:

- Self Service phone banking, for journeys such as "retrieve my balance"
- Authentication by phone, for journeys such as "approve my request" (using a personal identification code, PIN).
- Assisted phone banking, for common support with payments and emergency services (stolen card and others)
- Dedicated access to teams handling customer cases for products such as loans and mortgages .
- Dedicated access to individual agents that service small and midsize companies or private banking
- Request a call back on an ING website. Instantly: Call me now or scheduled: Call me later.
 
These customer journeys are powered by a high available network infrastructure and many routing and workflow features. These handle opening hours, routing based on skill and availability, as well as escalation when customers are waiting too long.

..note::
Since voice is such a well-known, established, channel - the ING voice solution does not include a client for our customers. It is quite natural for them to use their own phone of choice to reach ING. And to keep things clear, the numbers made available for our customers are the exact same numbers in use today. But can of course be changed or extended if required.

Assisted and Self service
--------------------------
In classic telephony technology we would refer to the PBX, the ACD and the IVR. The Twilio cloud platform offers and contains all three together. This allows us to make available, in the ING Twilio solution, assisted and self-service numbers (for customers).

Assisted voice contains routing rules that deliver incoming calls to agents. As is the case today, a certain number can be delivered to defined teams (and agents with the correct skill). An example of this is the 24*7 help line that customers can reach out to when they experience problems with their banking services. When agents in these teams reach out proactively, their team-number will be displayed (to the customer) to show its ING calling. When needed, this can also be a personal number or an anonymous number. The solution allows this to be set per person. 

Call flows
-----------
?Assisted voice can be made more smart and efficient by adding features to the call treatment of the inbound call. Basic features, such as a greeting, a regular of emergency message and opening hours (per number) are part of the ING voice solution. Additionally, advanced features such as natural language recognition and typing numbers enable creation of so called call flows that improve routing of inbound calls. Examples are: Requesting the customer to type their account number to include their profile in routing decisions. And a customer can also be requested to either choose or speak the topic of their call. 

For agents and supervisors
--------------------------
For agents, the voice channel enables reaching out to customers. Of course this can be done manually using the toolbar. But it can also be automated by using the dialer features. These help the agent setting up calls quickly and keep track of customers reached. 

For supervisors, the voice channel reports extensive management information to the dashboards. These show the current number of active voice calls for a team, as well as the current status of their members. Since this data is also kept, it can also be used to see trends and analyze both customer behavior and agent productivity.

With service!
-----------------
Underneath all this sits an ING in-house IT service. The voice channel is delivered and maintained by multiple ING teams that together deliver a high available network and 24*7 support and monitoring. With this approach, we ensure the availability of the voice channel for both ING customers and agents. 

Voice building blocks
------------------------
The voice product has a few building blocks: 

1. PSTN Numbers, that your customers dial
2. A call flow configuration (that determines the call treatment) and
3. A workflow configuration (that determines the group of agents that should receive the incoming call). 
4. And for outbound calling: Configuration of the CLI

Here is a short guide to finding additional information about these topics. 

For obtaining PSTN numbers, as well as migration of your existing numbers, please visit this Confluence page that has detailed instructions on how to do it (Confluence Europe).

For understanding of the Call flow and its options, it's best to start here. 
If you need more information than available here, please reach out to the onboarding squad. 

For understanding the Call flow and speech recognition, this page helps.
