# DESCRIBE
- Can you get the real meaning from this file.
Download the file here.
- ***Hints***:Engaging in various decoding processes is of utmost importance
# SOLUTION
- When we access the file, we will see an undecrypted encryption. To decode, we need tools to support this decoding.
- Tools to decode are:https://www.dcode.fr/
- Initially, when the encoding is in the form `YidkM0JxZGtwQlRYdHFhR3g2YUhsZmF6TnFlVGwzWVROclgyeG9OakJzTURCcGZRPT0nCg==`, we check and see that the encoding is in the form of base64.
- After we decode base64, we will get another encoding `b'd3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrX2xoNjBsMDBpfQ=='`. This is the encoding that has not been decoded yet. Let's decode it again and we will get an encoding `wpjvJAM{jhlzhy_k3jy9wa3k_lh60l00i} `.This is the encoding we need to use dcode to decode.
- Flag:	picoCTF{caesar_d3cr9pt3d_ea60e00b}
