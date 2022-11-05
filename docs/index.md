![Bridge Buttons logo, a blue bridge connected to a blue onion](bb_transparent.png)

Bridge Buttons are one of the easiest ways to stand up for the journalists, activists, and vulnerable citizens around the world that depend on Tor to use the internet safely. Tor is an anonymity network that helps keep its users anonymous by routing their internet traffic through multiple different machines run by volunteers, which results in their location and identity being concealed. Unfortunately regimes around the world have blocked access to Tor, which is why Tor bridges were created. They are brand-new access points these regimes do not know about that can be rapidly deployed and torn down faster than they can be blocked, letting these users get back online!

Bridge Buttons let you deploy a Tor bridge with a single click to any Amazon Web Services (AWS) region. These bridges come pre-configured to stay with in AWS' free tier for one year! While you will be prompted for a payment method when first signing up for AWS, these bridges are configured to use AWS' free computing product and have a Tor configuration that caps the bandwidth passing through your bride at under 15GB.

# What is a Tor bridge?

You will be acting as an access point to the Tor network. Your bridge is a computer that will relay traffic for these users to their next Tor relay, but the key is that your bridge is never listed publicly. This makes it difficult for it to be blocked. It also helps hide that a user is connecting to Tor since they won't be connecting to a machine publicly connected to Tor.

# Is hosting a Tor bridge safe?

You may have heard that it can be potentially dangerous to run a Tor exit node, where traffic exits the Tor network. These are different from Tor bridges. Your bridge will not be publicly listed. Your bridge also is an entry point- an exit node makes the final connection to the website the user requests and therefore appears to be doing the "browsing".

# If my bridge isn't publicly listed, how to people get to it?

Tor distributes bridges to users who request them over email, or via https://bridges.torproject.org/. This makes it difficult for adversaries to compile a list of all Tor bridges and block them, since the number that are distributed at a time is limited.

# How do I deploy my bridge?

First, sign up for an AWS account [here](https://portal.aws.amazon.com/billing/signup#/start/email). While you will be prompted for payment information, your bridge is expected to run on the free tier.

Next, find the region you would like to deploy to in the world and click the corresponding button. Consider deploying your bridge closer to a region that needs Tor bridges. For example, if you wish to help Iranian activists consider deploying to Bahrain.

| Region | Bridge Button |
|--------|---------------|
| US East (Ohio)       | [![Create Bridge](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=torbridge&templateURL=https://bridgebuttons.s3.amazonaws.com/tor-bridge-cloudformation.yml)              |
| US East (N. Virginia)       | [![Create Bridge](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=torbridge&templateURL=https://bridgebuttons.s3.amazonaws.com/tor-bridge-cloudformation.yml)                   |
| US West (N. California)       |               |
| US West (Oregon)       |               |
| Africa (Cape Town)       |               |
| Asia Pacific (Hong Kong)       |               |
| Asia Pacific (Jakarta)       |               |
| Asia Pacific (Mumbai)       |               |
| Asia Pacific (Osaka)       |               |
| Asia Pacific (Seoul)       |               |
| Asia Pacific (Singapore)       |               |
| Asia Pacific (Sydney)       |               |
| Asia Pacific (Tokyo)       |               |
| Canada (Central)       |               |
| Europe (Frankfurt)       |               |
| Europe (Ireland)       |               |
| Europe (London)       |               |
| Europe (Milan)       |               |
| Europe (Paris)       |               |
| Europe (Stockholm)       |               |
| Middle East (Bahrain)       |               |
| Middle East (UAE)       |               |
| South America (São Paulo)       |               |