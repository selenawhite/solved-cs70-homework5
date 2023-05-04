Download Link: https://assignmentchef.com/product/solved-cs70-homework5
<br>



Simplify each expression using Fermat’s Little Theorem.

<ul>

 <li>3<sup>33 </sup>(mod 11)</li>

 <li>10001<sup>10001 </sup>(mod 17)</li>

 <li>10<sup>10 </sup>+20<sup>20 </sup>+30<sup>30 </sup>+40<sup>40 </sup>(mod 7)</li>

</ul>

<h1>2          RSA Practice</h1>

Bob would like to receive encrypted messages from Alice via RSA.

<ul>

 <li>Bob chooses <em>p</em>= 7 and <em>q</em>= His public key is (<em>N</em><em>,e</em>). What is <em>N</em>?</li>

 <li>What number is <em>e </em>relatively prime to?</li>

 <li><em>e </em>need not be prime itself, but what is the smallest prime number <em>e </em>can be? Use this value for <em>e </em>in all subsequent computations.</li>

 <li>What is gcd(<em>e</em><em>,</em>(<em>p</em>−1)(<em>q</em>−1))?</li>

 <li>What is the decryption exponent <em>d</em>?</li>

 <li>Now imagine that Alice wants to send Bob the message 30. She applies her encryption function <em>E </em>to 30. What is her encrypted message?</li>

</ul>

CS 70, Fall 2018, HW 5                                                                                                                                                                          1

<ul>

 <li>Bob receives the encrypted message, and applies his decryption function <em>D </em>to it. What is <em>D </em>applied to the received message?</li>

</ul>

<h1>3          Squared RSA</h1>

<ul>

 <li>Prove the identity <em>a<sup>p</sup></em><sup>(<em>p</em></sup><sup>−1</sup><sup>) </sup>≡ 1 (mod <em>p</em><sup>2</sup>), where <em>a </em>is coprime to <em>p</em>, and <em>p </em>is prime. (Hint: Try to mimic the proof of Fermat’s Little Theorem from the notes.)</li>

 <li>Now consider the RSA scheme: the public key is (<em>N </em>= <em>p</em><sup>2</sup><em>q</em><sup>2</sup><em>,e</em>) for primes <em>p </em>and <em>q</em>, with <em>e </em>relatively prime to <em>p</em>(<em>p</em>− 1)<em>q</em>(<em>q</em>− 1). The private key is <em>d </em>= <em>e</em><sup>−1 </sup>(mod <em>p</em>(<em>p</em>− 1)<em>q</em>(<em>q</em>− 1)). Prove that the scheme is correct for <em>x </em>relatively prime to both <em>p </em>and <em>q</em>, i.e. <em>x<sup>ed </sup></em>≡<em>x </em>(mod <em>N</em>).</li>

 <li>Prove that this scheme is at least as hard to break as normal RSA; that is, prove that if this scheme can be broken, normal RSA can be as well. We consider RSA to be broken if knowing <em>pq </em>allows you to deduce (<em>p</em>−1)(<em>q</em>−1). We consider squared RSA to be broken if knowing <em>p</em><sup>2</sup><em>q</em><sup>2 </sup>allows you to deduce <em>p</em>(<em>p</em>−1)<em>q</em>(<em>q</em>−1).</li>

</ul>