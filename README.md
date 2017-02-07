# PoC-xss
examples of how data can be transferred after an xss injection

The html file shows basically four examples on how data might be secretly transferred after a successful xss injection.

- classic XMLHttpRequest - this is limited due to Access-Control-Allow-Origin - but worth checking out.
- use of hidden image tags where the src=\<targetURL\>
- use of hidden iframe tags similar to the above the src=\<targetURL\>
- modification of an existing link on the compromised webpage

Check out the html code for above mentioned examples.

Warning! This is meant for educational purpose only! Use it in a contained environment. Using this in the wild in combination with xss attacks is illegal in most countries! So don't! You have been warned.

Best

