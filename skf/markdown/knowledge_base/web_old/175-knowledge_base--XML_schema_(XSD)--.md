##Description:

When adding schema's to your or XML files you have better control over what type of user-input can be supplied in your application. This dramatically decreases an attacker’s vector when implemented the right way. Nonetheless, you should always apply your own input validation and rejection as an extra layer of defense. This approach is also desirable since you also want to do countering and logging on the user’s requests and input.	 

##Mitigation:

Verify that XSD schema validation takes place to ensure a properly formed XML document, followed by validation of each input field before any processing of that data takes place.

