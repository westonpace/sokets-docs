## REGISTRAR BOT
![Photo of a DMV worke- I mean registrar bot](/images/registrar.jpg)

Welcome to the collective.  Before you proceed to be integrated with the collective you must complete the registration task.  I am by law required to state that integrating with a collective of formless beings may or may not have long lasting impacts on your health.  No state agency oversees or regulates the collective.  Proceed at your own risk.  The registration process requires you to follow protocol 273-4B.  Here is a document which explains the process.  Thank you for contacting the collective.  Please exit through the door on your left.

### Protocol 273-4B

Protocol 273-4B was developed by a team of interns to establish an individual's connection with the collective.  We are proud to report that 75% of the interns survived.  The process is detailed in case study 1208L.  

 1. Connect with the registrar on port 5001.
 2. Once the connection is established the registrar will then transfer your personalized 32 byte key.  You are responsible for the storage and maintenance of the key.  The collective does not take responsibility for your bits.
 3. Promptly transfer the registrar's name "registrar" to the registrar
 4. Promptly transfer your name to the registrar
 5. Receive your 24 byte registration token
 6. Provide the registration token to the handler as a hex encoded string without spaces

 The name transfer process is defined in more detail in appendix C

 Thanks to the tireless efforts of intern 923761 we now have a graphical representation of protocol 273-4B for beings with ocular capabilities.

 ![Literally just lines and arrows describing what I just wrote.  I don't know why this would help anyone but sighted individuals always need their diagrams.](/images/registrar-protocol.png)

### Protocol 273-4B Appendix C

 * All names shall be signed using the advanced encryption standard in electronic codebook mode.
 * All names shall be 128 bytes.  If your name is not 128 bytes it shall be right padded with the UTF character U+0000.  If your name is more than 128 bytes or includes the U+0000 character then please follow exception process guillotine.
 
### Challenge Questions

For individuals that wish to seek to improve their knowledge of protocol 273-4B we provide challenge questions. Please DM your answers to individual Ximvu to avoid spreading confusion and/or clarification of protocol 273-4B on public channels.

 1. The encryption cipher in this task is using a fairly simple encryption mode.  If someone were to capture traffic to this bot then what could they learn about the names of the users?
 2. There is a bit of a pattern to the registration tokens.  Can you figure out what it is?  How does this reduce the entropy of the registration tokens?

### Hints

Through the misadventures of several interns it has been brought to our attention that hints should be made available to reduce the load on our support staff and avoid another occurrence of something like incident 9713.

<details>
<summary>
Hint 1 (expected transfer size)
</summary>
Due to the encryption process you may think you need to transfer more than 128 bytes.  You don't.  If you get to a point where you are thinking this then print your bytes encoded as hex and check if you notice anything odd about any of them.
</details>
<details>
<summary>
Hint 2 (expected output given a certain key)
</summary>
If you were provided the key (hex) `9384c90bc10e4aea2881c97fbe2657cc28e21e0d8b31a2b8d7b737a7c952005c` then your first response should be (hex) `2a030b6cd1c38343064f963895829eaef13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2` and your second response should be (hex) `12ea4a829434c0e35f1dceff6f947a91f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2f13cbd5121cf7a80eaed832de89460a2` provided of course that your name was Ximvu.
</details>
