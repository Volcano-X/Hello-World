# On markdown

## You can create a new paragraph by leaving a blank line between lines of text.

Please remember that markdown always ignores the blank and Enter. So if you want to renew a paragraph, you should leave a new line to note that. For example, the following two examples show this problem. 

This doc introduce markdown in github. 
Now I want to begin as a new paragraph.

This doc introduce markdown in github:(you must have a blank line).

Now I want to begin as a new paragraph.

## New line and blank
If you want to begin the text as a new line but not a paragraph, you can type \<br/> at the right of the text. e.g.: 

This doc introduce markdown in github. 
Now I want to begin as a new line.

This doc introduce markdown in github. <br/>
Now I want to begin as a new line.

This doc introduce markdown in github.(you also can type 2/2+ space so as to have a new line[^2])  
Now I want to begin as a new line.


## Mathematical Formulation
Here is a inner-line math formulation: 
$\mathrm{Tr}(X) =  \mathbf{X}Z$

Here is a embedding-line math formulation:(you must have a blank line)

$$
\min_{Z}  \ \frac{1}{2}||X-XZ||_F^2 + \lambda  \ Tr( XLX^T), \quad s.t. \ \mathrm{diag}(Z) = 0, \ Z \geq 0.
$$

Here is a embedding-blocked math formulation:(you must have a blank line)

$$
\begin{equation}
\begin{split}
&\min_{Z}  \ \frac{1}{2}\|X-XZ\|_F^2 + \lambda  \ Tr( XLX^T), \\ 
&s.t. \ \mathrm{diag}(Z) = 0, \ Z \geq 0.
\end{split}
\end{equation}
$$

Here is a embedding-blocked math formulation:(you must have a blank line)

$$
\begin{align}
E_{\ell} &= \alpha \left( I + \alpha Z_{\ell} Z_{\ell}^T \right)^{-1}. \\
C_{\ell}^j &= \alpha_j \left( I + \alpha_j Z_{\ell} \Pi^j Z_{\ell}^T \right)^{-1}.
\end{align}
$$

## List
(To make the md code more robust, I suggest to leave a blank line as necessary as it need.)

How to make a list? (To begin a list, maybe you donnot need to leave a blank link, but it is suggested to leave):

+ fds
+ fasddf
+ fsdf
+ sdfds fsdfsd

How to make a nested list?(To be unified, Intend space is suggested to have 4 space): 

1. fsdf
    + fsdf
        - fsdfs
            * fsdf
          

## Other should be noticed
Hide some content from render markdown. 
<!-- This content will not appear in the rendered Markdown -->


The AI Conference List: 
- [x] prepare for ICML
- [x] prepare for NIPS
- [x] prepare for ICLR
- [x] prepare for CVPR
- [ ] prepare for ICCV
- [ ] prepare for KDD
- [x] prepare for AAAI
- [x] prepare for IJCAI
- [ ] prepare for MM
- [ ] prepare for WWW
- [ ] prepare for WSDM

The AI Journal List:
- [x] prepare for TPAMI
- [x] prepare for JMLR
- [x] prepare for IJCV
- [ ] prepare for TIP
- [ ] prepare for TNNLS
- [x] prepare for TCYB
- [x] prepare for TKDE
- [ ] prepare for TMM
- [ ] prepare for TCSVT
- [ ] prepare for PR

@Volcano-can, be careful, I will paste a image here! ![You can type some remarks of the image, e.g. This is a cat](https://myoctocat.com/assets/images/base-octocat.svg)

[To a quick start of Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), [To a specific doc of markdown in github](https://github.github.com/gfm/#paragraphs)


<sub>This is a subscript text</sub> <sup>This is a superscript text</sup>

Citation:

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].



[^1]:
    My reference. Noted the footnote is numbered by the citation number.
[^2]: 
    Every new line should be prefixed with **2 spaces**.  
    This allows you to have a footnote with multiple lines.
[^note]: 
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
