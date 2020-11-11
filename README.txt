Student #1
Joseph Grosso
20010435
15jjg6
Student #2
Kati Camacho
20069849
17klc

COMMENTS

For the modulatePixels function, I used a slighly different method to compute the log and exponent of the value for the fourier transform pixels. Below is my logic I sent to the prof for why I used this alternative calculation.

Hi Prof Stewart, 

I'm emailing because I have a concern about the behaviour of the suggested modulatePixels formula from assignment 2. Below is a link to the Desmos graph I used to compare the behaviour of both the suggested solution and of the solution I am currently using. Let me know if this link doesn't work.

https://www.desmos.com/calculator/iajvyx6qsa

I believe the code is improved with this method because x^m behaves exactly like e(ln(x)*m), which is not true of e(ln(x+1)*m)-1. It is also more easily readable than the other method in my opinion because it can be computed in one line in Python.  

Best Regards,
Joe Grosso

For the above reasons I applied the factor to the Fourier transform using the x^factor method instead of calculating e(ln(x+1)*m)-1.
