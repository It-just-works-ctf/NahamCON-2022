# The Smuggler

**Category** : Networking
**Points** : 500

<small>Author: @Kkevsterrr#7469</small><br><br>Argh! We've got a custom border firewall to filter out DNS requests that aren't so cool before we send them on to 1.1.1.1 for processing. To get the flag, all you need to do is to send us DNS request for <code>nahamcon.com</code> to which 1.1.1.1 will accept and correctly respond. The problem is that our firewall is going to refuse to send any well-formed DNS request for <code>nahamcon.com</code>. Your task is to craft a (technically malformed/non-compliant) DNS request to which 1.1.1.1 will still correctly respond (but that our firewall will ignore) to sneak your request by our pesky firewall. A DNS smuggler, you be!<br><br><i>Fun fact - this challenge is modeled after a real vulnerability in the Great Firewall of China's DNS censorship system.</i> <br> <br> <b>Press the <code>Start</code> button on the top-right to begin this challenge.</b>




