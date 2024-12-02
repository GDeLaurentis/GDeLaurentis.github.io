---
title: Reconstruction of analytical amplitudes across loops, legs and theories
summary: 
authors: ["Giuseppe De Laurentis"]
tags: [QCD, Scattering Amplitudes, CHY]
categories: []
date: "2019-11-08T00:00:00Z"
markup: blackfriday
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: sky
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---
<html>
	<head>
		<link rel="stylesheet" href="../reveal_custom.css">
	</head>
</html>

{{< slide background-image="Durham.png" >}}

### <font face=arial> <b> Reconstruction &nbsp; of &nbsp; analytical &nbsp; amplitudes <br> &nbsp; across &nbsp; loops, &nbsp; legs &nbsp; and &nbsp; theories </b> </font face>

[arXiv:1904.04067](https://arxiv.org/abs/1904.04067) [(JHEP)](https://link.springer.com/article/10.1007/JHEP07(2019)123) &nbsp; &nbsp; [arXiv:1910.11355](https://arxiv.org/abs/1910.11355)

<br>
Giuseppe De Laurentis

with Daniel Maître

IPPP Internal Seminar

<img src="IP3_logo_blue.png"; style="max-width:280px;float:center;border:none;"> <img src="DurhamLogo.svg"; style="max-width:280px;float:center;border:none;">

{{< speaker_note >}}
- Only speaker can read these.
- Press S to view.
{{< /speaker_note >}}

---

# Table &nbsp;of &nbsp;Contents

<br>

**A. &nbsp; Reconstruction of analytical spinor-helicity amplitudes**

*1. Motivation* &nbsp; &nbsp; *2. Singular limits* &nbsp; &nbsp; *3. Partial fractions and ansatze* <br>

*4. Rational coefficients in QCD*

<br>

**B. &nbsp; Tree amplitudes from the CHY formalism**

*1. Motivation* &nbsp; &nbsp; *2. Scattering equations* &nbsp; &nbsp; *3. CHY-Integrands* &nbsp; &nbsp; *4. Amplitudes*

---

<font size=9>
**A. &nbsp; Reconstruction of analytical<br> &nbsp; &nbsp; &nbsp; spinor-helicity amplitudes**
</font size>

---

<section>

# A&nbsp;1.1 &nbsp; Motivation

---

<b> Cross sections at hadron colliders </b>
<br>

<font size=5>
$σ_{2 \rightarrow n - 2} = ∑\_{a,b} ∫ dx_a dx_b f\_{a/h_1}(x_a, μ_F) \, f\_{b/h_2}(x_b, μ_F) \;\hat{σ}\_{ab→n-2}(μ_F, μ_R)$

$d\hat{σ}\_{n}=\frac{1}{2\hat{s}}dΠ\_{n-2}\;(2π)^4δ^4\big(∑\_{i=1}^n p_i\big)\;|\overline{\mathcal{A}(p_i,μ_F, μ_R)}|^2$
</font size>

<br>
Better predictions require both more loops and higher multiplicity.

<font size=5>

<table width=50% border="1" cellspacing="0" cellpadding="0" style="margin-bottom:-10px">
  <tr class="greenline">
    <td colspan="2", rowspan="2"> <div id="rot90"> <center> <b> $\mathcal{A}_{mult.}^{loops} \propto g_s^n $ </b> </center> </div> </td>
    <td colspan="4"> <center> <b> multiplicity </b> </center> </td>
  </tr>
  <tr>
    <td><b>4</b></td>
    <td><b>5</b></td>
    <td><b>6</b></td>
    <td><b>7</b></td>
  </tr>
  <tr>
    <td rowspan="3"> <b> loops </b> </td>
    <td><b>0</b></td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
  </tr>
  <tr>
    <td><b>1</b></td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
  </tr>
  <tr>
    <td><b>2</b></td>
    <td>6</td>
    <td>7</td>
    <td>8</td>
    <td>9</td>
  </tr>
</table>

</font size>

<font size=5>Powers of coupling in pure gluon scattering.</font size>
 

---

<b> Chromo-dynamics and kinematics </b>
<br>

Color ordering at tree level and one loop \[[1](https://pdf.sciencedirectassets.com/271560/1-s2.0-S0550321300X14241/1-s2.0-0550321387906043/main.pdf?X-Amz-Security-Token=AgoJb3JpZ2luX2VjEAIaCXVzLWVhc3QtMSJGMEQCIGNVZuaBsYoWqvtaF%2BAgxc5mpOVy4bMGH2V9AEodTcd4AiAndJhl3k7SA%2Fe2SXVKYCT1Ul4lUrLqXFWVacr%2B1j4YoyraAwhbEAIaDDA1OTAwMzU0Njg2NSIMZCFFK5U%2BuBvoYbtnKrcDAVoIqqSxnZJyWIxHsBuGbbV8ceVrgQ5eYutSzPdHjcMUaIoJlhOXuu2VWIwI6OyG1X3N8KDE816wZTkqwIJT4sU0I7V60zDOZVuZqwDcIom6o5AOm3gPwFYPUE%2B922vgv%2BJT3XwNiqNtjSC00ZFjbectcM7nJa7YWcWAjkZi3oJkIRPvn5m2oOMWET0jR6ZHWhy2jyM7zyiq1oxrXG4JYKB78hua2lVMc3BPdsSombpNeiebjXU4y2Fl35pz8lYIr3Nyws7P91pJS9%2Fzmqjf9QqVHMhjtMWJvQPsYDx%2BJa3UpXT9jo4r1LIERU5%2BZ%2BmVwpqjUqm3jdmvn1p9A3NaxqjyB%2FxfYp6PxAeFmmFi6hlo3IfqGLVoWsTrz0JfNH3L2ADYZhQW8y8QroshqK97GTQqlYbRORZAQeHEILoSjiVDz%2F%2BvT4UupJjaWpECMUca6%2FmrFA3h9KslrYNS%2BxskX0jxleuKkIfdjwoHcES0VA2nq9ELc%2Bhc9Va5T8Wpix7kANcqwOdZtFT5qQSmFOj4e32hzXfefbtqvC4iVBkWMSnvcE4MP3ulM0ac66RuzXZmFnFFzrIHlDDQnozpBTq1AfOoqS7ORld3jyfBg%2FPRvpifiXb3yYmCI1efBvG1zniZHaUld2etzPTcDEWFMm%2FPPAiA5N3c6cL7qQ4xoNuJu6II%2FCVex8l3pxr1LMZxhjcbu24lIRKPxjmN%2BbnMiCCU8VFhR24vzt8cDyKIyUXFIK7qY3OUqcwGDywoER1Ew1y0QvRwtMY8mCBaLbG5oMNSnj7Uf5fQzeKdXs6Dg6fvv4BtNLCR1wFyNDb1T3oNmpT3JEabGG4%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20190708T094930Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYZF2Y5ZNJ%2F20190708%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e91db2a858f3b014276b08879802905aaa8b6b99a9a2693fb585b8ada55b9148&hash=0a71e9d7ca1ef201e5ba2b048cea87b8566aa5c71a9df0903d2ea6a86c687cdc&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=0550321387906043&tid=spdf-d25eb1ed-dd86-4e45-80cb-1e3c295697ff&sid=5c9de57e2ed3984ef69997d0bb7d4e65ff39gxrqb&type=client), [2](https://pdf.sciencedirectassets.com/271560/1-s2.0-S0550321300X15143/1-s2.0-055032139190567H/main.pdf?X-Amz-Security-Token=AgoJb3JpZ2luX2VjEAIaCXVzLWVhc3QtMSJIMEYCIQD3re8xFPROG2g0iYThs9UNoSNDMKhroRYo0TMSTHZPMwIhAIEVIYT2ghbXJ5W1YvREYQ%2BE8agWUgV1vLbq8nv01II4KtoDCFsQAhoMMDU5MDAzNTQ2ODY1Igysg9ZJldbBrlxNevkqtwOKrvNA%2B8nRTloFiexgu%2FS8oCZHTo4dckrAatSr8SX44XC4V8cbhwOWNQw%2BaUCkYN3vXjUyKd5CUFEAMNKtMKWQL12DhZXgmcLRN7TloRABrIVlY1zx7Q15w0dHkFqBqd%2FaNp4tTbDN5KqTZhiyrgFwU6%2BW7YPlWFqhFqQy215RAsWL4noNHf%2B%2Bq4hA6JXZJJSX%2B%2FLcNRR%2FYyPO%2FBLX%2BD0LYfkSqKz9w7lP29C7%2BWxzQmhyKIXgZOL9hcqp2tEZ55WWSmI6N8wWzXuQYhZ4thP368NFMFd8UN133rnrOhew1xJZcEBIRN50U66TkH7mXduwRFoYB%2BkQqve6I0v9sO4XgEVlSAbhr4LjxZJY%2FlYoFUcIl11EJZDGWkid%2Fm2b%2FB25VT8uvAYSFJ4NM9XUNZmskfeoQ1hGVjRs0hSRsC8PfXFSsS9QumI2MFCKV4w4azjdlkR7N3n8IAGlHQi%2BkZ5T%2B9iUSiTt%2F3znT3pwgg4OCsXTd4oWDNjv6peO50NqGk7k9OxlR0UFhvqTT3nHkzliChGcjrI%2FOo32I%2BAPHcWjsv7qB%2FwPKc4T%2FNlkhPWZKXuJMs5k3xrvMK2ajOkFOrMBkz1BJSpBnB2pM2cVxQZSOVyCbY3SLI8NJBKP7nn3qbav%2Bj%2BqrD1IkW5ZxwaN%2B%2FxGNKrr0YZrOwmZmr7GAoBqLGm17gEFdqfy5%2F6yoMOwFu1upyDVlydHvoxNhRliesqqvxNtoAjNQUF%2FfECJZ1IAhHf7DcnmSTyINrWzVgi%2ByQqiTqSJUQWSQ7%2BJMUy97THP7GuQpNCitwnXIo9PwbNTVixfCiy37rxMAFWwpo%2FLEITtpPs%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20190708T095217Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYRUVXQZXE%2F20190708%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=35625627d2cae627f9c59d0ea06ec3cf70419b248446a401b304d94cd91a5fd0&hash=b819decaf33c29230d1b66317b3be006fc68534d24f4f0887c6367e38898d15a&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=055032139190567H&tid=spdf-59fd60cb-6bbb-4016-9779-87c46ad6d585&sid=5c9de57e2ed3984ef69997d0bb7d4e65ff39gxrqb&type=client), ...\]:

<font size=5>$\mathcal{A}^{tree}\_{n}({p_i, λ_i, a_i}) = \; g^{n-2} ∑\_{σ\in S_n/Z_n} \text{Tr}(T^{a_σ(1)}\dots T^{a_σ(n)}) A^{tree}_n(σ(1^{λ_1}),\dots ,σ(n^{λ_n}))$</font size>

<font size=5; style="margin-left:-20px;">
$\mathcal{A}^{1-loop}\_{n}({p\_i, λ\_i, a\_i}) = \; g^{n} ∑\_{σ\in S\_n/Z\_n} N\_{c} \text{Tr}(T^{a\_σ(1)}\dots T^{a\_σ(n)}) A\_{n;1}(σ(1^{λ\_1}),\dots ,σ(n^{λ\_n}))$
</font size>
<font size=5; style="margin-left:-50px;">
$ + ∑\_{c = 2}^{\lfloor n/2 \rfloor + 1}∑\_{σ\in S\_n/Z\_{n;c}} \text{Tr}(T^{a\_σ(1)}\dots T^{a\_σ(c-1)})\text{Tr}(T^{a\_σ( c)}\dots T^{a\_σ(n)}) A\_{n;c}(σ(1^{λ\_1}),\dots ,σ(n^{λ\_n}))$</font size>
</font size>

<br>
Decomposition in terms of basis integrals \[[3](https://pdf.sciencedirectassets.com/271560/1-s2.0-S0550321300X15684/1-s2.0-0550321379906059/main.pdf?X-Amz-Security-Token=AgoJb3JpZ2luX2VjEAIaCXVzLWVhc3QtMSJGMEQCIGNVZuaBsYoWqvtaF%2BAgxc5mpOVy4bMGH2V9AEodTcd4AiAndJhl3k7SA%2Fe2SXVKYCT1Ul4lUrLqXFWVacr%2B1j4YoyraAwhbEAIaDDA1OTAwMzU0Njg2NSIMZCFFK5U%2BuBvoYbtnKrcDAVoIqqSxnZJyWIxHsBuGbbV8ceVrgQ5eYutSzPdHjcMUaIoJlhOXuu2VWIwI6OyG1X3N8KDE816wZTkqwIJT4sU0I7V60zDOZVuZqwDcIom6o5AOm3gPwFYPUE%2B922vgv%2BJT3XwNiqNtjSC00ZFjbectcM7nJa7YWcWAjkZi3oJkIRPvn5m2oOMWET0jR6ZHWhy2jyM7zyiq1oxrXG4JYKB78hua2lVMc3BPdsSombpNeiebjXU4y2Fl35pz8lYIr3Nyws7P91pJS9%2Fzmqjf9QqVHMhjtMWJvQPsYDx%2BJa3UpXT9jo4r1LIERU5%2BZ%2BmVwpqjUqm3jdmvn1p9A3NaxqjyB%2FxfYp6PxAeFmmFi6hlo3IfqGLVoWsTrz0JfNH3L2ADYZhQW8y8QroshqK97GTQqlYbRORZAQeHEILoSjiVDz%2F%2BvT4UupJjaWpECMUca6%2FmrFA3h9KslrYNS%2BxskX0jxleuKkIfdjwoHcES0VA2nq9ELc%2Bhc9Va5T8Wpix7kANcqwOdZtFT5qQSmFOj4e32hzXfefbtqvC4iVBkWMSnvcE4MP3ulM0ac66RuzXZmFnFFzrIHlDDQnozpBTq1AfOoqS7ORld3jyfBg%2FPRvpifiXb3yYmCI1efBvG1zniZHaUld2etzPTcDEWFMm%2FPPAiA5N3c6cL7qQ4xoNuJu6II%2FCVex8l3pxr1LMZxhjcbu24lIRKPxjmN%2BbnMiCCU8VFhR24vzt8cDyKIyUXFIK7qY3OUqcwGDywoER1Ew1y0QvRwtMY8mCBaLbG5oMNSnj7Uf5fQzeKdXs6Dg6fvv4BtNLCR1wFyNDb1T3oNmpT3JEabGG4%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20190708T100628Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIAQ3PHCVTYZF2Y5ZNJ%2F20190708%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=d919ed9ae7a1959e538a14b0201a53f55ff2d050c159575173ea8c207d452dc2&hash=566c1a9bb320be2e7a96e7b9501740e9f7a65fb676b3ea2ba759c1154fa6e5c5&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=0550321379906059&tid=spdf-de178cac-e602-4007-a06a-590f35e6031e&sid=5c9de57e2ed3984ef69997d0bb7d4e65ff39gxrqb&type=client), [4](https://arxiv.org/pdf/hep-ph/9212308.pdf), [5](https://arxiv.org/pdf/0712.1851.pdf), ...\]:

<font size=5>
$$A^{1-loop}\_{n;1} = \sum\_i d\_i I^i\_{Box} + \sum\_i c\_i I^i\_{Triangle} + \sum\_i b\_i I^i\_{Bubble} + R$$

<nobr>$A^{tree},\, d\_i,\, c\_i,\, b\_i,$ and $R$ are rational functions of kinematic invariants only.</nobr>

</font size>

---

<b> Intermediate and final expressions  </b>
<br>

Brute force calculations are a mess:

<img src="Five_gluons_mess.png"; style="max-width:500px;float:center;border:none;margin-top:-5px;">

Results are often much easier [[6](https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.56.2459),
[7](https://reader.elsevier.com/reader/sd/pii/0550321388904427?token=EFDF378B5E170FFAF0B1BECE184A1EB6304F7798C481CF3C0E7D93DF6D367AE0E093D4D4942C932C66E8BEB75DAB41FE)]:


<font size=5>

$A^{tree}(1^{+}\_{g}2^{+}\_{g}3^{+}\_{g}4^{-}\_{g}5^{-}\_{g}) = \frac{i\,⟨45⟩^{4}}{⟨12⟩⟨23⟩⟨34⟩⟨45⟩⟨51⟩}$

</font size>

---

<b> Numerical and Analytical: pros and cons </b>
<br>

*Numerical* calculations efficiently bypass algebraic complexity, see:<br/>
<font size=4> <nobr> BlackHat \[[8](https://arxiv.org/abs/0803.4180)\], CutTools [[9](https://arxiv.org/abs/0711.3596)], MadGraph [[10](https://arxiv.org/abs/1106.0522)], Rocket [[11](https://arxiv.org/abs/0805.2152)], Samurai [[12](https://arxiv.org/abs/1006.0710)], NGluon [[13](https://arxiv.org/abs/1011.2900)], OpenLoops [[14](https://arxiv.org/pdf/1111.5206.pdf)]... </nobr> </font size>

<br>
But *analytical* results can still be useful, they can provide:
<table width=100% border="1" frame="void" cellspacing="0" cellpadding="0">
  <tr>
      <td>
	<font size=5>
	$\cdot$ faster computation<br/>
    	$\cdot$ better numerical stability<br/>
    	$\cdot$ easier to distribute than a program<br/>
	</font size>
      </td>
      <td>
      <font size=5>
    	$\cdot$ possible to compile on a GPU<br/>
    	$\cdot$ explicit analytical structure<br/>
    	$...$
      </font size>
      </td>
  </tr>
</table>

<br>
How can we access a (relatively) compact analytical final expression from numerical evaluations?

</section>
---
---

<section>
# A&nbsp;1.2 &nbsp;Spinor &nbsp;Helicity

---

<b> Lowest-laying representations of the Lorentz group </b>
<br>

<font size=5>
(Recall: $\mathfrak{so}(1, 3)_\mathbb{C} \sim \mathfrak{su}(2) \times \mathfrak{su}(2)$)
</font size> 

<font size=5>

| $\boldsymbol{(j\_{-},j\_{+})}$ | dim. | name | quantum field | kinematic variable |
| :-------------: | :-------------: | :------------- | :-------------: | :-------------: |
| (0,0) | 1 | scalar | $h$ | m |
| (0,1/2) | 2 | right-handed Weyl spinor | $\chi_{R\,\alpha}$ | $\lambda_\alpha$ |
| (1/2,0) | 2 | left-handed Weyl spinor | $\chi_L^{\,\dot\alpha}$ | $\bar{\lambda}^{\dot\alpha}$ |
| (1/2,1/2) | 4 | rank-two spinor/four vector | $A^\mu/A^{\dot\alpha\alpha}$ | $P^\mu/P^{\dot\alpha\alpha}$ |
| (1/2,0)$\oplus$(0,1/2) | 4 | bispinor (Dirac spinor) | $\Psi$ | $u, v$ |

</font size>

---

<b> Spinors </b>
<br>

Weyl spinors are sufficient for massless particles:

<font size=5>$\text{det}(P^{\dot\alpha\alpha})=m^2 \rightarrow 0 \quad \Longrightarrow \quad P^{\dot\alpha\alpha} = \bar\lambda^{\dot\alpha}\lambda^\alpha$.</font size>

<br>
In terms of 4-momentum components we have:

<font size=5>$$
\lambda\_\alpha=\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^0+p^3 \\\ p^1+ip^2\end{pmatrix} \, , \;\;\; \lambda^\alpha=\epsilon^{\alpha\beta} \lambda_\beta =\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^1+ip^2 \\\ -p^0+p^3\end{pmatrix}
$$</font size>

<font size=5>$\bar\lambda\_{\dot\alpha}=\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^0+p^3 \\\ p^1-ip^2\end{pmatrix} \, , \;\;\; \bar\lambda^{\dot\alpha}=\epsilon^{\dot\alpha\dot\beta}\bar\lambda_{\dot\beta}=\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^1-ip^2 \\\ \-p^0+p^3\end{pmatrix}$</font size>

<br>

<font size=5>$$
\bar\lambda\_{\dot\alpha} = (\lambda\_\alpha)^* \quad if \quad p^i \in \mathbb{R}; \quad \quad \bar\lambda\_{\dot\alpha} \neq (\lambda\_\alpha)^* \quad if \quad p^i \in \mathbb{C}
$$</font size>

---

<b> Spinor Helicity </b>
<br>

<font size=5>
$$
⟨ij⟩ = λ_iλ_j = (λ_i)^α(λ_j)_α \quad \quad \quad [ij] = \barλ_i\barλ_j = (\barλ_i)\_\dotα(\barλ_j)^\dotα
$$


$$
s_{ij} = ⟨ij⟩[ji]
$$


$$
⟨i\;|\;(j+k)\;|\;l] = (λ_i)^α (\not P_j + \not P_k )\_{α\dotα} \barλ_l^\dotα
$$


$$
⟨i\;|\;(j+k)\;|\;(l+m)\;|\;n⟩ = (λ_i)^α (\not P_j + \not P_k )\_{α \dot α} (\bar{\not P_l} + \bar{\not P_m} )^{\dot α α} (λ_n)_α
$$


$$
tr_5(ijkl) = tr(\gamma^5 \not P_i \not P_j \not P_k \not P_l) =  [i\,|\,j\,|\,k\,|\,l\,|\,i⟩ - ⟨i\,|\,j\,|\,k\,|\,l\,|\,i]
$$

</font size>

---

<b>Why use complex momenta?</b>

<br>

We want to be able to distinguish between different poles.<br><br>
For example, we want to tell apart:

$$
\frac{1}{⟨ij⟩} \quad and \quad \frac{1}{[ji]}
$$

but with real momenta we would have:

$$
⟨ij⟩ \sim [ji]^* \sim \sqrt{s_{ij}}
$$

</section>
---
---

<section>
# A&nbsp;2.1 &nbsp;Singular &nbsp;limits

---

<b>Singular limits $\Rightarrow$ poles of the amplitude</b>
<br>

We need a set of Lorentz invariants:

<font size=5>$r\_i \in \\{ ⟨12⟩, ⟨13⟩, \dots, ⟨1|2+3|4], \dots, s_{123}, \dots \\}$,</font size>

and let $\, \mathbb{f} \,$ be the function we want to reconstruct.

<br>

<nobr> We want to build phase space points where <u style="text-decoration: underline;
  text-decoration-color: red;"> a single invariant vanishes</u>: </nobr>

<font size=5> $r\_i \rightarrow ε \ll 1, \quad r\_{j \neq i} \sim \mathcal{O}(1), \quad \mathbb{f} \rightarrow ε^α \; \Rightarrow \; log(\mathbb{f}) \rightarrow α\cdot log(ε)$</font size>

<nobr>$\Rightarrow$ The slope of the log-log plot gives us the type of singularity, if it exists.</nobr>

<br>
<nobr>The uniqueness of the singular limit is important to avoid ambiguities,</nobr>
and it can be guaranteed only with complex momenta.

---

<b>Tree-level example</b>
<br>

<font size=5>

$\mathbb{f} = A^{tree}(1^{+}\_{g}2^{+}\_{g}3^{+}\_{g}4^{-}\_{g}5^{-}\_{g}6^{-}\_{g})$

<table width=100% border="1" frame="void" cellspacing="0" cellpadding="0" style="margin-bottom:-20px">
  <tr class="greenline">
    <td> <center> $\lim_{⟨12⟩ \rightarrow \epsilon} \mathbb{f} \propto \epsilon^{-1}$ </center> </td>
    <td> <center> $\lim_{⟨13⟩ \rightarrow \epsilon} \mathbb{f} \propto \epsilon^0$ </center> </td>
  </tr>
  <tr>
    <td> <img src="lim12.png"; style="max-width:450px;float:center;border:none;"> </td>
    <td> <img src="lim13.png"; style="max-width:450px;float:center;border:none;"> </td>
  </tr>
</table>

</font size>

<font size=5> Note: the invariant on the x-axis gets smaller from left to right.</font size>

---

<b>The least common denominator</b>
<br>

Studying all the limits yields the least common denominator for $\mathbb{f}$:

$\mathbb{f} = \frac{\mathcal{N\_{LCD}}}{\mathcal{D\_{LCD}}} = \frac{\mathcal{N\_{LCD}}}{⟨12⟩⟨16⟩[16]⟨23⟩⟨34⟩[34][45][56]s\_{234}s\_{345}}$.


<font size=5>

<br>

The complexity of the numerator depends on two parameters:

1. mass dimension; $\quad \quad \quad$ 2. little group scalings.

<br>

<nobr> In this case $\mathcal{N\_{LCD}}$ has mass dimension 10, and phase weights [-1, 0, -1, 1, 0, 1].</nobr>

The ansatz has 1326 independent terms.

</font size>

</section>
---
---

<section>
# A&nbsp;2.2 &nbsp;Doubly &nbsp;singular &nbsp;limits

---

<b>Partial fractioning</b>

<br>

Except for the easiest cases, we should really think about $\mathbb{f}$ as:
<br>

$\mathbb{f} = \sum\_i \frac{\mathcal{N}_i}{\mathcal{D}_i} = \sum\_i \frac{\mathcal{N}_i}{\mathcal{R}_i\mathcal{S}_i}$,
<br>

where $\mathcal{R}\_i$ are products of subsets of $\mathcal{D\_{LCD}}$ (i.e. real poles), <br/> and $\mathcal{S}\_i$ are products of factors not in $\mathcal{D_{LCD}}$ (i.e. spurious poles).

---

<b>Doubly singular limits</b>

<br>

The required information can be accessed from doubly singular limits.

We now want phase space points where <u style="text-decoration: underline;
  text-decoration-color: red;"> two invariants vanish</u>:

$r\_i \rightarrow ε \ll 1, \quad r\_j \rightarrow ε \ll 1, \quad \mathbb{f} \rightarrow ε^α \; \Rightarrow \; log(\mathbb{f}) \rightarrow α\cdot log(ε)$

<br>

In general we cannot guarantee uniqueness anymore,<br/> even with complex momenta.<br/> $\exists \;r\_{k \neq i, j} \sim \epsilon$.


---

<b>Information from doubly singular limits</b>
<br>

<font size=5>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>⟨1|2⟩</th>
      <th>⟨1|6⟩</th>
      <th>[1|6]</th>
      <th>⟨2|3⟩</th>
      <th>⟨3|4⟩</th>
      <th>[3|4]</th>
      <th>[4|5]</th>
      <th>[5|6]</th>
      <th>s_234</th>
      <th>s_345</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>⟨1|2⟩</th>
      <td>1</td>
      <td>1, 30</td>
      <td>1, 3</td>
      <td>1, 31</td>
      <td>1, 2</td>
      <td>2, 12</td>
      <td>2, 3</td>
      <td>2, 10</td>
      <td>1, 2</td>
      <td>2, 10</td>
    </tr>
    <tr>
      <th>⟨1|6⟩</th>
      <td>1, 30</td>
      <td>1</td>
      <td>1, 2</td>
      <td>1, 2</td>
      <td>1, 10</td>
      <td>2, 4</td>
      <td>2, 12</td>
      <td>1, 3</td>
      <td>2, 10</td>
      <td>2, 10</td>
    </tr>
    <tr>
      <td colspan="11"> <center> $\dots$ </center> </td>
    </tr>
    <tr>
      <th>s_234</th>
      <td>1, 2</td>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>1, 2</td>
      <td>2, 10</td>
      <td>1</td>
      <td>1, 2</td>
    </tr>
    <tr>
      <th>s_345</th>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>1, 2</td>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>2, 10</td>
      <td>1, 2</td>
      <td>1, 2</td>
      <td>1</td>
    </tr>
  </tbody>
</table>

</font size>

The first number is the slope of the log-log plot in the limit, <br/> the second number is the degeneracy of the phase space in the limit.

<br>
Let's introduce the following notation, which we'll need later: $\\{a, b\\}\_\epsilon$.<br/>
It represents the set of all invariants that vanish when $a$ and $b$ vanish.<br/> For example:<br/>
<font size=5>$\\{⟨12⟩,\,⟨16⟩\\}\_\epsilon = \\{ ⟨12⟩, ⟨16⟩, ⟨26⟩, s\_{345}, ⟨2|1+6|5], \dots \text{25 more} \dots \\}$</font size>

---

<b>Which poles share the same denominator?</b>
<br>

<!--- The slope in the doubly singular limit tells us whether two poles should be in the same denominator and the degeneracy how to separate them. --->

The following is single line of the table in the previous slide:
<font size=5>

<style type="text/css">
    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col0 {
            background:  tomato;
            background:  tomato;
            background:  tomato;
            background:  tomato;
            background:  tomato;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col1 {
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col2 {
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col3 {
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col4 {
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col5 {
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col6 {
            background:  tomato;
            background:  tomato;
            background:  tomato;
            background:  tomato;
            background:  tomato;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col7 {
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
            background:  skyblue;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col8 {
            background:  khaki;
            background:  khaki;
            background:  khaki;
            background:  khaki;
            background:  khaki;
        }    #T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col9 {
            background:  tomato;
            background:  tomato;
            background:  tomato;
            background:  tomato;
            background:  tomato;
        }</style>  
<table id="T_67e20e68_9da2_11e9_b9bf_0242a8af999f" style="margin-top:-70px;" ><caption align="bottom">Green: forced. Red: forbidden. Blue: optional (at least one). Light blue: optional.</caption> 
<thead>    <tr> 
        <th class="blank level0" ></th> 
        <th class="col_heading level0 col0" >⟨1|2⟩</th> 
        <th class="col_heading level0 col1" >⟨1|6⟩</th> 
        <th class="col_heading level0 col2" >[1|6]</th> 
        <th class="col_heading level0 col3" >⟨2|3⟩</th> 
        <th class="col_heading level0 col4" >⟨3|4⟩</th> 
        <th class="col_heading level0 col5" >[3|4]</th> 
        <th class="col_heading level0 col6" >[4|5]</th> 
        <th class="col_heading level0 col7" >[5|6]</th> 
        <th class="col_heading level0 col8" >s_234</th> 
        <th class="col_heading level0 col9" >s_345</th> 
    </tr></thead> 
<tbody>    <tr> 
        <th id="T_67e20e68_9da2_11e9_b9bf_0242a8af999flevel0_row0" class="row_heading level0 row0" >s_234</th> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col0" class="data row0 col0" > 1 ,  2 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col1" class="data row0 col1" > 2 ,  10 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col2" class="data row0 col2" > 2 ,  10</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col3" class="data row0 col3" > 2 ,  10 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col4" class="data row0 col4" > 2 ,  10 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col5" class="data row0 col5" > 2 ,  10 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col6" class="data row0 col6" > 1 ,  2 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col7" class="data row0 col7" > 2 ,  10 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col8" class="data row0 col8" > 1 </td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col9" class="data row0 col9" > 1 ,  2 </td> 
    </tr></tbody> 
</table>

</font size>

<img src="Graph.gv.svg"; style="max-width:720px;float:center;border:none;margin-bottom:-30px;">

<font size=5> Diagramatic representation of relation between poles</font size>

</section>
---
---

<section>
# A&nbsp;3.1 &nbsp;Partial &nbsp;fraction &nbsp;decomposition

---

<b> Partial fraction decomposition #1 </b>
<br>

<!--- Going back to our tree level example,<br/> let's see how we can group together the poles of the amplitude. --->

<table width=100% border="1" frame="void" cellspacing="0" cellpadding="0">
  <tr class="greenline">
    <td> <center> <img src="Graph2.gv.svg"; style="max-width:540px;float:center;border:none;"> </center> </td>
    <td>
      <center>
        <font size=6>
	  ${\small A^{tree}(1^{+}_{g}2^{+}_{g}3^{+}_{g}4^{-}_{g}5^{-}_{g}6^{-}_{g}) = }\\
	    \frac{\mathcal{N_1}}{[16]⟨23⟩⟨34⟩[56]⟨2|1+6|5]s_{234}}+\\
	    \frac{\mathcal{N_2}}{⟨12⟩⟨16⟩[34][45]⟨2|1+6|5]s_{345}}\phantom{+}$
        </font size>
      </center>
    </td>
  </tr>
</table>

<font size=5>(Spoiler: $ \quad \small \mathcal{N_1} = 1i⟨4|2+3|1]^3, \quad \mathcal{N_2} = -1i⟨6|1+2|3]^3$)</font size>

Where does <font size=5> $⟨2|1+6|5]$ </font size> come from?

<font size=5>$\\{⟨12⟩, [56]\\}\_{\epsilon} \, \cap \, \\{⟨16⟩, s\_{234}\\}\_{\epsilon} \, \cap \, \\{⟨23⟩, [45]\\}\_{\epsilon} \, \cap \, \\{[34], s\_{234}\\}\_{\epsilon} \, \dots$ </font size>

---

<b> Partial fraction decomposition #2 </b>
<br>

<table width=100% border="1" frame="void" cellspacing="0" cellpadding="0">
  <tr class="greenline">
    <td> <center> <img src="Graph3.gv.svg"; style="max-width:540px;float:center;border:none;"> </center> </td>
    <td>
      <center>
        <font size=6>
	  $\frac{\mathcal{N_1}}{⟨16⟩[34]⟨1|2+3|4]⟨5|1+6|2]s_{234}}+\\$
	  $\frac{\mathcal{N_2}}{[16]⟨34⟩⟨3|1+2|6]⟨5|1+6|2]s_{345}}+\\$
	  $\frac{\mathcal{N_3}}{⟨12⟩⟨23⟩[45][56]⟨1|2+3|4]⟨3|1+2|6]}$
        </font size>
      </center>
    </td>
  </tr>
</table>

<font size=5>(Spoiler: $ \quad \small \mathcal{N_1} = 1i[23]^3⟨56⟩^3, \quad \mathcal{N_2} = -1i[12]^3⟨45⟩^3, \quad \mathcal{N_3} = 1is\_{123}^3 $)</font size>

<font size=5>$⟨1|2+3|4] = \\{⟨12⟩, [34]\\}\_{\epsilon} \, \cap \, \\{⟨23⟩, s\_{234}\\}\_{\epsilon} \, \cap \, \\{⟨16⟩, [45]\\}\_{\epsilon} \, \cap \, \dots$</font size>
<font size=5>$⟨3|1+2|6] = \\{⟨23⟩, [16]\\}\_{\epsilon} \, \cap \, \\{⟨12⟩, s\_{345}\\}\_{\epsilon} \, \cap \, \\{⟨34⟩, [56]\\}\_{\epsilon} \, \cap \, \dots$</font size>

Both of these partial fractions correspond to some BCFW shift,<br/> but we are not limited to these representations.

---

<b> Partial fraction decomposition #3 </b>
<br>

<table width=100% border="1" frame="void" cellspacing="0" cellpadding="0">
  <tr class="greenline">
    <td> <center> <img src="Graph.gv.svg"; style="max-width:540px;float:center;border:none;"> </center> </td>
    <td>
      <center>
        <font size=6>
	  $\frac{\mathcal{N_1}}{[16]⟨23⟩⟨34⟩[56]s_{234}s_{345}}+\\$
	  $\frac{\mathcal{N_2}}{⟨12⟩⟨16⟩[34][45]s_{234}s_{345}}+\\$
	  $\frac{\mathcal{N_3}}{⟨12⟩⟨23⟩[45][56]s_{234}s_{345}}$
        </font size>
      </center>
    </td>
  </tr>
</table>

<font size=5> <nobr> ($\small \mathcal{N_1} = 1i[12]⟨45⟩⟨4|2+3|1]^2, \, \mathcal{N_2} = 1i[23]⟨56⟩⟨6|1+2|3]^2, \, \mathcal{N_3} = 1i⟨4|2+3|1]⟨6|1+2|3]s\_{123}$) </nobr> </font size>

We now have no spurious poles, but $s\_{234}$ and $s\_{345}$ appear in the same denominator, although the doubly singular limit suggests they shouldn't.

This means that in the limit of $\\{s\_{234}, s\_{345}\\} \rightarrow \epsilon$ the individual terms will behave like $\epsilon^{-2}$ but the sum as $\epsilon^{-1}$.

Different representations can be exploited to ensure numerical stability.

</section>
---
---

<section>
# A&nbsp;3.2 &nbsp;Fitting &nbsp;of &nbsp;ansatz

---

<b> Spinor ansatz </b>
<br>

Let's consider the first representation:

$\mathbb{f}=$
$\frac{\mathcal{N\_1}}{[16]⟨23⟩⟨34⟩[56]⟨2|1+6|5]s\_{234}}+$
$\frac{\mathcal{N\_2}}{⟨12⟩⟨16⟩[34][45]⟨2|1+6|5]s\_{345}}$

<br>
$\mathcal{N\_1}$ has mass dimension: 6, and phase weights: [-3, 0, 0, 3, 0, 0].<br/>
<!--- We generate all possible products of spinor products compatible with this infomation. ---> The ansatz has size 10:

$[⟨24⟩⟨24⟩⟨24⟩[12][12][12],$
$⟨24⟩⟨24⟩⟨34⟩[12][12][13],$
$⟨24⟩⟨24⟩⟨45⟩[12][12][15],$
$⟨24⟩⟨34⟩⟨34⟩[12][13][13],$
$⟨24⟩⟨34⟩⟨45⟩[12][13][15],$
$⟨24⟩⟨45⟩⟨45⟩[12][15][15],$
$⟨34⟩⟨34⟩⟨34⟩[13][13][13],$
$⟨34⟩⟨34⟩⟨45⟩[13][13][15],$
$⟨34⟩⟨45⟩⟨45⟩[13][15][15],$
$⟨45⟩⟨45⟩⟨45⟩[15][15][15]]$,

much smaller than the one for $\mathcal{N_{LCD}}$<br/> which had more than 1000 terms!

---

<b> Gaussian elimination </b>
<br>

$\mathbb{f}=$
$\frac{\mathcal{N\_1}}{[16]⟨23⟩⟨34⟩[56]⟨2|1+6|5]s\_{234}}+$
$\frac{\mathcal{N\_2}}{⟨12⟩⟨16⟩[34][45]⟨2|1+6|5]s\_{345}}$

Isolate the first term by generating phase space points <br/> in the limit of, say, $s_{234} \rightarrow \epsilon$.

Then we can reconstruct the numerical coefficient of the ansatz entries by Gaussian elimination.

$$
M_{ij}c_j = \mathbb{f}(P_i) \quad \text{i.e.} \quad \begin{pmatrix} \leftarrow ansatz(P_1) \rightarrow \\\ \leftarrow ansatz(P_2) \rightarrow \\\ \dots \end{pmatrix} \cdot \begin{pmatrix} c_1 \\\ c_2 \\\ \dots \end{pmatrix} = \begin{pmatrix} \mathbb{f}(P_1) \\\ \mathbb{f}(P_2) \\\ \dots \end{pmatrix}
$$

We get:

<font size=5>
$⟨24⟩⟨24⟩⟨24⟩[12][12][12]: 1i$,  $⟨24⟩⟨24⟩⟨34⟩[12][12][13]: 3i$, <br/>
$⟨24⟩⟨34⟩⟨34⟩[12][13][13]: 3i$,  $⟨34⟩⟨34⟩⟨34⟩[13][13][13]: 1i$
</font size>

---

<b> How big is the ansatz? </b>

Easiest to count at constant null phase weights;<br/> the size of the ansatz is a function of:<br/><br/>1. its mass dimension ($d$) $\quad\quad$ 2.  multiplicity of phase space ($m$).

<br>
If we allow only for a polynomial in the numerator, then:

$|s\_{ij}| = \frac{m(m-3)}{2}$ $\quad\quad$ $|tr\_5| = {m-1 \choose 4}$

$\left(\mkern -9mu \begin{pmatrix}\, |s\_{ij}| \, \\\ \, d/2 \, \end{pmatrix} \mkern -9mu \right) \leq$ ansatz size $\leq \left(\mkern -9mu  \begin{pmatrix} \, |s\_{ij}| \, \\\ \, d/2 \, \end{pmatrix} \mkern -9mu \right) + |tr_5| \left(\mkern -9mu  \begin{pmatrix} \, |s\_{ij}| \, \\\ \, (d-4)/2 \, \end{pmatrix} \mkern -9mu \right)$

The upper bound is saturated for $(\forall m \wedge d \leq 4)$ and for $(\forall d \wedge m \leq 5)$.<br/>
Otherwise it is an overcounting due to Schouten identity for 4-momenta:
<font size=5>$tr\_5(2345)1\_\mu - tr\_5(1345)2\_\mu + tr\_5(1245)3\_\mu - tr\_5(1235)4\_\mu + tr\_5(1234)5\_\mu = 0$</font size>

</section>
---
---

<section>
# A&nbsp;4.1 &nbsp; Rational &nbsp; coefficients &nbsp; in &nbsp; QCD

---

<b> Six-gluon one-loop rational coefficients </b>

<br>
As an application we obtained analytical expressions for all parts of the six-gluon amplitude with a gluon in the loop.

<br>
All independent coefficients are available as anchillary files at: [arXiv:1904.04067](https://arxiv.org/abs/1904.04067).

<br>
Our expressions are manifestly rational and gauge invariant.

<br>
For a summary of the litterature see Ref.[15](https://arxiv.org/pdf/0901.1202.pdf).

---

<b> Three mass triangle </b>
<br>

<img src="three_mass_triangle.svg"; width=25%; height=25%; style="float:center;border:none;margin-bottom:0px;">

<font size=5>$\mathcal{D\_{LCD}} = ⟨12⟩[12]⟨34⟩[34]⟨56⟩[56]⟨1|3+4|2]^4⟨3|1+2|4]^4⟨5|1+2|6]^4Δ_{135}^3$</font size>

An expression was previously obtained in [[16](https://arxiv.org/pdf/hep-ph/0602178.pdf)].

We obtain an explicitly rational expression, like for $\mathcal{N}=1$ SUSY in [[17](https://arxiv.org/pdf/0709.2086.pdf)].

---

<b> Pole structure </b>

<table width=70% border="1" frame="void" cellspacing="0" cellpadding="0">
  <tr class="greenline">
    <td> <center> <img src="Graph5.gv.svg"; style="max-width:360px;float:center;border:none;"> </center> </td>
    <td>
      <center>
        <font size=4>
	Symmetries:<br/>
	  $123456$<br/>
	  $\overline{216543}$<br/>
 	  $345612$<br/>
 	  $\overline{432165}$<br/>
	  $561234$<br/>
	  $\overline{654321}$<br/>
        </font size>
      </center>
    </td>
  </tr>
</table>

<font size=3>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>⟨12⟩</th>
      <th>[12]</th>
      <th>⟨34⟩</th>
      <th>[34]</th>
      <th>⟨56⟩</th>
      <th>[56]</th>
      <th>⟨1|3+4|2]</th>
      <th>⟨3|1+2|4]</th>
      <th>⟨5|1+2|6]</th>
      <th>Δ_135</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>⟨1|2⟩</th>
      <td>1</td>
      <td>1, 2</td>
      <td>1, 2</td>
      <td>2, 12</td>
      <td>1, 2</td>
      <td>2, 12</td>
      <td>4, 4</td>
      <td>5, 6</td>
      <td>2, 10</td>
      <td>2, 4</td>
    </tr>
    <tr>
      <td colspan="11"> <center> $\dots$ </center> </td>
    </tr>
    <tr>
      <th>⟨3|1+2|4]</th>
      <td>5, 6</td>
      <td>2, 10</td>
      <td>4, 4</td>
      <td>4, 4</td>
      <td>2, 10</td>
      <td>5, 6</td>
      <td>4, 2</td>
      <td>4</td>
      <td>4, 2</td>
      <td style="background:yellow">3.5, 4</td>
    </tr>
    <tr>
      <td colspan="11"> <center> $\dots$ </center> </td>
    </tr>
  </tbody>
</table>

</font size>

---

<b>Do we need square roots of momentum invariants?</b>
<br>

All branch cuts should have been taken care of by unitarity cuts.

We should be able to explain this without using square roots.

<br>
The culprit is $\Delta$, which first appears in the <br/> three mass triangle momentum parametrisation:

<font size=5>$\Delta\_{135} = (K\_1 \cdot K\_2)^2 - K\_1^2 K\_2^2$</font size>

<br>
Solution:<br/>
In some limits $\Delta$ behaves like the square of some quantity

<font size=5 style="margin-left:-75px;">$(\Omega\_{351})^2 \equiv (2s\_{12}s\_{56}-(s\_{12}+s\_{56}-s\_{45})s\_{123})^2 = 4s\_{123}^2\Delta\_{135}-4s\_{12}s\_{56}\langle 4|1+2|3]\langle 3|1+2|4]$</font size>

<font size=5>$(\Pi\_{351})^2 \equiv (s\_{123}-s\_{124})^2 = 4\Delta\_{135}-4\langle 4|1+2|3]\langle 3|1+2|4]$</font size>

---

<!--- <iframe src="https://arxiv.org/src/1904.04067v3/anc/AllOneLoop6Gluons/6g_pmpmpm_G/triangle_19_.pdf&embedded=true" style="width:718px; height:700px;" frameborder="0"></iframe> --->

<b> The three-mass triangle rational coefficient </b>

<font size=4>
$$
\begin{gathered}
\scriptscriptstyle \frac{-1/2i⟨23⟩^3[45]^3s\_{123}^2Ω\_{351}}{⟨12⟩[56]⟨1|2+3|4]⟨3|1+2|4]^4⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle \frac{1/4i[12]⟨23⟩^3[45]^3⟨56⟩⟨4|1+2|3]s\_{123}Π\_{351}}{⟨1|2+3|4]⟨3|1+2|4]^3⟨3|1+2|6]Δ\_{135}}+\\\\\\
\scriptscriptstyle \frac{2i⟨23⟩^2[45]^2⟨2|1+3|5]s\_{123}Ω\_{351}}{⟨12⟩[56]⟨1|2+3|4]⟨3|1+2|4]^3⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle \frac{⟨2|3+4|1]⟨6|1+2|5]Ω\_{351}(1i⟨12⟩[12]⟨13⟩[13]\,...⟪4\,\text{terms}⟫...\, -1i⟨23⟩[23]⟨35⟩[35])}{⟨1|3+4|2]⟨3|1+2|4]^2⟨5|1+2|6]Δ\_{135}}+\\\\\\
\scriptscriptstyle \frac{4i⟨12⟩^3[12]^2[13][15]⟨36⟩\,...⟪65\,\text{terms}⟫...\, -4i[12]⟨23⟩^2[23]⟨26⟩[35]⟨36⟩[36]}{⟨1|3+4|2]⟨3|1+2|4]^2⟨5|1+2|6]}+\\\\\\
\scriptscriptstyle \frac{[12]⟨23⟩^3[45]^3⟨56⟩⟨4|1+2|3]^2Π\_{351}(1/8is\_{123}+1/16is\_{124})}{⟨1|2+3|4]⟨3|1+2|4]^2⟨3|1+2|6]Δ\_{135}^2}+\\\\\\
\scriptscriptstyle \frac{-3i⟨23⟩[45]⟨2|1+3|5]^2Ω\_{351}}{⟨12⟩[56]⟨1|2+3|4]⟨3|1+2|4]^2⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle \frac{⟨23⟩\[45\](-4i⟨12⟩^2[12]^2[15]⟨26⟩\,...⟪31\,\text{terms}⟫...\, +4i[12]⟨26⟩^2⟨56⟩[56]^2)}{⟨1|2+3|4]⟨3|1+2|4]^2⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle \frac{5/32i⟨12⟩[12]⟨34⟩[34]⟨56⟩[56]⟨2|3+4|1]⟨4|1+2|3]⟨6|1+2|5]Π\_{351}}{⟨1|3+4|2]⟨3|1+2|4]⟨5|1+2|6]Δ\_{135}^2}+\\\\\\
\scriptscriptstyle \frac{⟨2|3+4|1]⟨4|1+2|3]⟨6|1+2|5]⟨1|3+4|1]⟨56⟩\[56\](-1/4i⟨12⟩[12]⟨23⟩[23]\,...⟪17\,\text{terms}⟫...\, +1/4i⟨24⟩[24]⟨34⟩[34])}{⟨1|3+4|2]⟨3|1+2|4]⟨5|1+2|6]Δ\_{135}^2}+\\\\\\
\dots\\\\\\
\scriptscriptstyle (123456\; \rightarrow \; 345612)+\\\\\\
\scriptscriptstyle (123456\; \rightarrow \; 561234)+\\\\\\
\dots
\end{gathered}
$$
</font size>
<!---
$$
\begin{gathered}
\scriptscriptstyle \frac{⟨2|3+4|1]⟨4|1+2|3]⟨6|1+2|5]⟨2|3+4|2]⟨56⟩[56](-1/4i⟨12⟩[12]⟨23⟩[23]\,...⟪7\,\text{terms}⟫...\, +1/2i⟨13⟩[14][35]⟨45⟩)}{⟨1|3+4|2]⟨3|1+2|4]⟨5|1+2|6]Δ\_{135}^2}+\\\\\\
\scriptscriptstyle \frac{⟨2|3+4|1]⟨6|1+2|5](7/4i⟨12⟩^2[12]^2[13]⟨14⟩\,...⟪47\,\text{terms}⟫...\, +3/2i⟨23⟩[23]^2⟨25⟩⟨34⟩[35])}{⟨1|3+4|2]⟨3|1+2|4]⟨5|1+2|6]Δ\_{135}}+\\\\\\
\scriptscriptstyle \frac{⟨23⟩^2[45]^2⟨4|1+2|3](5/4i⟨12⟩^2[12]^2[13]⟨14⟩[14]⟨46⟩\,...⟪152\,\text{terms}⟫...\, +5/8i[12]⟨26⟩⟨34⟩[34]⟨36⟩[36]^2⟨46⟩)}{⟨1|2+3|4]⟨3|1+2|4]⟨3|1+2|6]Δ\_{135}^2}+\\\\\\
\scriptscriptstyle \frac{-2i⟨2|1+3|5]^3s\_{123}}{⟨12⟩[56]⟨1|2+3|4]⟨3|1+2|4]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle \frac{3/16i⟨12⟩^2[12]^2⟨14⟩[14][15]⟨24⟩^2[25]⟨26⟩[34]\,...⟪1340\,\text{terms}⟫...\, +3i[13]⟨24⟩^2[24][25]⟨26⟩^4[26]^2[56]}{⟨1|2+3|4]⟨3|1+2|6]Δ\_{135}^2}+\\\\\\
\scriptscriptstyle \frac{-2i⟨24⟩[35]⟨2|1+3|5]^2}{⟨12⟩[56]⟨1|2+3|4]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle (123456\; \rightarrow \; 345612)+\\\\\\
\scriptscriptstyle (123456\; \rightarrow \; 561234)+\\\\\\
\scriptscriptstyle \frac{5/128i⟨12⟩[12]⟨34⟩[34]⟨56⟩[56]⟨2|3+4|1]⟨4|1+2|3]⟨6|1+2|5]Π\_{135}Π\_{351}Π\_{513}}{⟨1|3+4|2]⟨3|1+2|4]⟨5|1+2|6]Δ\_{135}^3}+\\\\\\
\scriptscriptstyle \frac{4i⟨12⟩^4[12]^3⟨13⟩[13][15]\,...⟪680\,\text{terms}⟫...\, +4i⟨23⟩^2[23]^2⟨25⟩⟨34⟩⟨35⟩[35]^2[45]}{⟨1|3+4|2]⟨1|2+3|4]⟨3|1+2|4]⟨3|1+2|6]⟨5|1+2|6]}+\\\\\\
\scriptscriptstyle \frac{-45i⟨12⟩^3[12]^2⟨13⟩[13]^2[23]⟨34⟩\,...⟪1160\,\text{terms}⟫...\, -4i⟨34⟩^2[34]^2⟨35⟩[35]^2⟨45⟩^2[45]}{⟨1|3+4|2]⟨1|2+3|4]⟨3|1+2|6]⟨5|1+6|2]⟨5|1+2|6]}\phantom{+}
\end{gathered}
$$
--->

---

<b>A six-gluon one-loop rational part</b>
<br>

<font size=5>
$R^{1-loop}\_6(1^{+}\_{g}2^{-}\_{g}3^{+}\_{g}4^{-}\_{g}5^{+}\_{g}6^{-}\_{g})$
</font size>

<font size=4>
$\mathcal{D\_{LCD}} =$
$⟨12⟩[12]⟨13⟩^2⟨15⟩^2⟨16⟩[16]⟨23⟩[23][24]^2[26]^2⟨34⟩[34]⟨35⟩^2⟨45⟩[45][46]^2⟨56⟩[56]$
$⟨1|2+3|1]^2⟨1|5+6|1]^2⟨1|3+4|2]^2⟨1|2+3|6]^2⟨2|1+6|2]^2⟨2|3+4|2]^2$
$⟨3|1+6|2]^2⟨3|1+2|3]^2⟨3|4+5|3]^2⟨3|1+2|4]^2⟨4|2+3|4]^2⟨4|5+6|4]^2$
$⟨5|1+6|4]^2⟨5|1+6|5]^2⟨5|3+4|5]^2⟨5|1+2|6]^2⟨6|1+2|6]^2⟨6|4+5|6]^2$
$s\_{123}s\_{234}s\_{345}Δ\_{135}^2Δ\_{624}^2$
</font size>

<font size=5>
The mass dimension is now 116,<br/>
which would imply an ansatz with size roughly $10^{10}$.

An analytical expression for this component was previously obtained in [[18](https://arxiv.org/pdf/hep-ph/0607017.pdf)] from Feynman diagrams.
</font size>

---

<b>The pole structure</b>
<br>

is a bit of a mess:

<img src="GraphRational.gv.svg"; style="maxwidth:1000px; float:center; border:none;">

---

<!--- <iframe src="https://arxiv.org/src/1904.04067v3/anc/AllOneLoop6Gluons/6g_pmpmpm_G/rational.pdf&embedded=true" style="width:718px; height:700px;" frameborder="0"></iframe> --->
<b> The rational part </b>

<font size=5>
$$
\begin{gathered}
\scriptscriptstyle\frac{2/3i⟨12⟩^3[15]^3[23]s\_{123}}{[45]⟨1|2+3|1]^2⟨1|2+3|4]⟨1|2+3|6]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle\frac{-2/3i⟨12⟩^3[15]^3[23]⟨3|1+2|5]}{⟨13⟩[45][56]⟨1|2+3|1]^2⟨1|2+3|4]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle\frac{1i⟨12⟩^3[15]^2⟨23⟩[23]^2[56]}{[45]⟨1|2+3|1]⟨1|2+3|4]⟨1|2+3|6]^2⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle\frac{⟨12⟩^2[15]^2\[23\](-1i⟨12⟩[15]+2i⟨23⟩[35])}{[45]⟨1|2+3|1]⟨1|2+3|4]⟨1|2+3|6]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle\frac{1i⟨12⟩^3[15]^2[25]⟨3|1+2|5]}{⟨13⟩^2[45][56]⟨1|2+3|1]⟨1|2+3|4]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle\frac{2i⟨12⟩^2[15]^2[35]⟨3|1+2|5]}{⟨13⟩[45][56]⟨1|2+3|1]⟨1|2+3|4]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle\frac{-1i⟨12⟩^2[15]⟨23⟩[25]^2⟨2|1+3|5]}{⟨13⟩^2[45][56]⟨1|2+3|4]⟨3|1+2|6]s\_{123}}+\\\\\\
\scriptscriptstyle\frac{-1i⟨12⟩^2[15]^2[25]⟨2|1+3|5]}{⟨13⟩[45][56]⟨1|2+3|4]⟨3|1+2|6]s\_{123}}+\\\\\\
\scriptscriptstyle\frac{⟨24⟩^2⟨26⟩^2(-1/6i⟨13⟩^2[13]⟨46⟩\,...⟪2\,\text{terms}⟫...\, +1/3i[12]⟨14⟩⟨16⟩⟨23⟩)}{⟨12⟩⟨16⟩⟨23⟩⟨34⟩⟨45⟩⟨56⟩⟨1|2+3|4]⟨3|1+2|6]}+\\\\\\
\scriptscriptstyle(123456\; \rightarrow \; \overline{234561})+
\scriptscriptstyle(123456\; \rightarrow \; 345612)+
\scriptscriptstyle(123456\; \rightarrow \; \overline{456123})+
\scriptscriptstyle(123456\; \rightarrow \; 561234)+
\scriptscriptstyle(123456\; \rightarrow \; \overline{612345})+\\\\\\
\scriptscriptstyle(123456\; \rightarrow \; \overline{654321})+
\scriptscriptstyle(123456\; \rightarrow \; 543216)+
\scriptscriptstyle(123456\; \rightarrow \; \overline{432165})+
\scriptscriptstyle(123456\; \rightarrow \; 321654)+
\scriptscriptstyle(123456\; \rightarrow \; \overline{216543})+
\scriptscriptstyle(123456\; \rightarrow \; 165432)+\\\\\\
\dots
\end{gathered}
$$
</font size>

---

<b> Five-partons two-loop remainders (preliminary results)</b>

The same strategy can be applied to other rational coefficients, <br>
e.g. two-loop finite remainders given in [[19](https://arxiv.org/abs/1904.00945)].

<img src="ratios.jpg"; style="max-width:560px;float:center;border:none;">

<font size=5>
Showing ratio of leaf counts for Mandelstam and spinor-helicity expressions (x-axis) vs. frequency (y-axis). The complexity is significantly reduced.
</font size>

---

<b> Example: uubggg pmpmp Nf1 #3 </b>

<img src="uubggg_pmpmp_nf1_nb3.png"; style="max-width:1024px;float:center;border:none;">

and

<font size=5>
$
-\frac{[32]^3 [41]^3}{2 [31]^3 [42]^3}
$
</font size>

are equivalent.

</section>
---
---
<section>

<font size=9>
**B. &nbsp; Tree amplitudes from the <br> CHY Formalism**
</font size>

</section>
---
---
<section>

# B&nbsp;1.1 &nbsp; Motivation

---

<b> Hidden relations ... </b>

Relations between amplitudes in different theories are often hidden in a standard Lagrangian quantum field theory formulation.

<br>

<font size=5>
$\mathcal{L_{Einstein Gravity}} = R\sqrt{-g} \quad \quad \mathcal{L\_{Yang Mills}} = -\frac{1}{4}F^{a\mu\nu}F^{a}\_{\mu\nu}$

$\mathcal{L\_{Biadjoint Scalar}} = 2∂^µΦ^{aa′}∂_µΦ^{aa′}+\frac{y}{3}f^{abc}\tilde f^{a′b′c′}Φ^{aa′}Φ^{bb′}Φ^{cc′}$
</font size>

<br>

E.g. the above are related by the KLT relations [[20](https://www.sciencedirect.com/science/article/pii/0550321386903627?via%3Dihub)], <br> more generally known as double copy relations.

---

<b> .. are made explicit </b>

By comparison in the CHY formalism [[21](https://arxiv.org/abs/1307.2199), [22](https://arxiv.org/abs/1309.0885), [23](https://arxiv.org/abs/1306.2962)] these relations are made explicit in the structure of the CHY-Integrands:

<br>

<font size=5>
$I_{CHY, Einstein Gravity} = PF'(\Psi) \; PF'(\tilde\Psi)$
</font size>

<font size=5>
$I\_{CHY, Yang Mills} = C_n \; PF'(\Psi) \quad \quad I\_{CHY, Biadjoint Scalar} = C_n \; C_n$
</font size>

<br>

Loosely speaking we have [[24](https://arxiv.org/abs/1306.6575)]:

$A = \int I\_{CHY} \quad$ and $\quad A\_{EG} = A\_{YM} \tilde A\_{YM} / A\_{BS}$ 

---

<b> Independent formulation </b>

<br>

<font size=5>

$\circ$ it does not rely on the Lagrangian or Feynman diagrams;

$\circ$ it is more efficient than a brute-force computation;

$\circ$ it is less efficient than recursion relations;

$\circ$ but the latter in some cases are not available.

</font size>

</section>
---
---
<section>

# B&nbsp;1.2 &nbsp; General Introduction

---

<b> Scattering equations and Riemann sphere </b>

The backbone of the CHY formalism are the scattering equations:

<font size=5>
$f\_a (z, k) \equiv \sum\limits_{b \in A \backslash \\{a\\}} \frac{k\_a \cdot k\_b}{z\_a - z\_b} = 0, \qquad \forall a \in A = \\{1, \dots, n\\}$
</font size>

The $k$'s are the momenta, and the $z$'s live on the Riemann sphere.

<figure>
	<img src="StereographicProjection.jpg"; style="max-width:480px;float:center;border:none;">
	<figcaption><font size=4>Figure: Stereographic projection from complex plane to Riemann sphere</font size></figcaption>
</figure>

---

<b> Möbius invariance or redundancy </b>

The scattering equations $f\_a$ are invariant under Möbius transformations:

<font size=5>
$z \rightarrow \zeta = \frac{\alpha z + \beta}{\gamma z + \delta}$.
</font size>

A Möbius transformation is obtained by performing the following operations on the Riemann sphere:

<table rules="all">
 <tr>
    <td><font size = 5>1) Translation $z \rightarrow \zeta = z + A$</font size></td>
    <td><font size = 5>2) Inversion $z \rightarrow \zeta = 1/z$</font size></td>
 </tr>
 <tr>
    <td><font size = 5>3) Rescaling $z \rightarrow \zeta = Bz$</font size></td>
    <td><font size = 5>4) Translation $z \rightarrow \zeta = z + C$</font size></td>
 </tr>
</table>

In general this allows us to fix three of the $z$'s:

<font size=5>
$z_1 = \infty, \quad z_2 = 1, \quad z_n = 0 \;$
</font size>

---

<b> Amplitudes from integrals </b>

The scattering amplitudes $\textit{A}\_n$ are given by:

<font size=5>
$\textit{A}\_n \, = \, i \int \frac{d^nz}{d\omega} \;\; I\_{\scriptscriptstyle CHY}(z; k; \epsilon) \prod'\_{a \in A} \delta(f\_a(z, k))$
</font size>

<font size=5>
$\; = \, i \oint\_\textit{O} \frac{d^nz}{d\omega} \;\; I\_{\scriptscriptstyle CHY}(z; k; \epsilon) \prod'\_{a \in A}\frac{1}{f_a(z,k)}$
</font size>

<br>

With the following definitions:

<font size=5>
$d\omega = \frac{dz_rdz_sdz_t}{(z_r-z_s)(z_s-z_t)(z_t-z_s)}$
</font size>

<font size=5>
$\prod'\_{a \in A} = (z\_i-z\_j)(z\_j-z\_k)(z\_k-z\_i)\prod_{a \in A \backslash \\{i,j,k\\}}$
</font size>

which make $\textit{A}\_n$ independent of the choice of <font size=5>$\\{i, j, k\\}$ and $\\{r, s, t\\}$</font size>.

---

<b> Amplitudes from sums </b>

In practice we want an algebraic equation of the amplitudes.

<br>

Change variables $z\_a \rightarrow f\_a$, $\,$ pick up a Jacobian:
  
$$ϕ_{ab}\, = \frac{∂ f_a}{∂ z_b}=
  \begin{cases}
    \frac{2 k\_a \cdot k\_b}{(z\_a - z\_b)^2} & a \neq b \; ,\\\\\\
    - \sum\limits\_{j \in A \backslash \{a\}} \frac{2 k\_a \cdot k\_j}{(z\_a - z\_j)^2} & a = b \; .
  \end{cases}$$

<br>

Integrate over the delta functions, set <font size=5>$\\{z_1, z_2, z_3\\} = \\{\infty, 1, 0\\}$</font size> get:

$\textit{A}\_n \, = \, z\_1^4 \cdot i \sum\_{j = 1}^{(n-3)!} \frac{I\_{\scriptscriptstyle CHY}(z^{(j)}(k); k; ϵ)}{\det(ϕ\_{rst}^{ijk})(z^{(j)}(k); k)}$

</section>
---
---
<section>

# B&nbsp;2. &nbsp; The scattering equations

---

<b> The original scattering equations </b>

This part of the computation depends only on the scattering multiplicity!<br>
No information about the thoery is required.

<br>

Solving the scattering equations (SE) is not trivial.

<font size=5>
$f\_a (z, k) \equiv \sum\limits_{b \in A \backslash \\{a\\}} \frac{k\_a \cdot k\_b}{z\_a - z\_b} = 0, \qquad \forall a \in A = \\{1, \dots, n\\}$
</font size>

If we simply take the common denominator we obtain a polynomial of much higher degree than necessary.

---

<b> The polynomial scattering equations </b>

Instead we are going to consider the polynomial SE <font size=5>$h\_{m}$</font size> from [[25](https://arxiv.org/abs/1402.7374)] 

<font size=5>
$h\_{m} = \sum\_{S \subset A',\, |S| = m} k^2\_{S\_1}z\_S=0 \, , \quad \text{with} \quad 1 \leq m \leq n - 3 \, ,$
</font size>

<font size=5>
$A' = A \backslash \\{1,n\\} \, , \quad S_1 = S \cup \{1\}$
</font size>

<font size=5>
$k\_S = \sum\_{b \in S} k\_b \quad \text{and} \quad z\_S = \prod\_{b \in S} z\_b$
</font size>

<br>

For example, for <font size=5>$n = 5$</font size>:

<font size=5>
$h\_1 = z\_2 k\_{\\{1,2\\}}^2+z\_3 k\_{\\{1,3\\}}^2+z\_4 k\_{\\{1,4\\}}^2$

$h\_2 = z\_2 z\_3 k\_{\\{1,2,3\\}}^2+z\_2 z\_4 k\_{\\{1,2,4\\}}^2+z\_3 z\_4 k\_{\\{1,3,4\\}}^2$
</font size>

---

<b> Elimination theory </b>

Needed for solving systems of polynomial equations. <br>
Just like Gaussian elimination is used for the linear case.

<br>

We can rewrite the two polynomial SE for <font size=5>$n = 5$</font size> as:

<font size=5>
$$
\left(
		\\begin{array}{cc}
		H & H^{z\_2} \\\\\\
		\\end{array}
		\\right)|\_{z\_2=0} \\cdot
		\\left(
		\\begin{array}{c}
		1\\\\\\
		{z\_2}\\\\\\
		\\end{array}
		\\right)=
		\\left(
		\\begin{array}{cc}
		z\_3 s\_{13}+ z\_4 s\_{14} & s\_{12} \\\\\\
		z\_3 z\_4 s\_{134} & z\_3 s\_{123} + z\_4 s\_{124} \\\\\\
		\\end{array}
		\\right) \\cdot
		\\left(
		\\begin{array}{c}
		1\\\\\\
		{z\_2}\\\\\\
		\\end{array}
		\\right)=0$$</font size>

Using the following simplified notation:

<font size=5>
$$
H = \\left(
    \\begin{array}{c}
	h\_1 \\\\\\
	h\_2 \\\\\\
    \\end{array}
    \\right) \; , \quad
H^{\sigma _2} = \\partial\_{z\_2}
    	      	\\left(
		\\begin{array}{c}
		h\_1 \\\\\\
		h\_2 \\\\\\
		\\end{array}
		\\right) \; , \quad
		k\_{\\{i,j,\\dots\\}}^2 = s\_{ij\\dots}
$$</font size>

---

<b> Five-point solutions </b>

Now taking the determinant of the matrix form of the SE we get:

<font size=5>
$$
\\det \left(
		\\begin{array}{cc}
		H & H^{z\_2} \\\\\\
		\\end{array}
		\\right)|\_{z\_2=0} = 0
$$
</font size>

<font size=5>
$$
z\_3^2 s\_{13} s\_{123} + z\_4 z\_3 ( s\_{14}  s\_{123} + s\_{13} s\_{124} - s\_{12} s\_{134} ) + z\_4^2 s\_{14} s\_{124} = 0 \; ,
$$
</font size>

This is the required quadratic in <font size=5>$ z\_4 / z\_3 $</font size> .

<br>

By reintroducing $z\_2$ and setting it to 1 we can then solve for $z\_4$ and $z\_3$:

<font size=3>
$$
z\_3 = \frac{-s\_{12} s\_{134} + s\_{123} s\_{14} - s\_{124} s\_{13} \pm
\sqrt{s\_{12}^2 s\_{134}^2 - 2 s\_{12} s\_{123} s\_{134} s\_{14} - 2 s\_{12} s\_{124} s\_{13} s\_{134} + s\_{123}^2 s\_{14}^2 - 2 s\_{123} s\_{124} s\_{13} s\_{14} + s\_{124}^2 s\_{13}^2}}{2 s\_{13} s\_{134}}
$$
$$
z\_4 = \frac{-s\_{12} s\_{134} - s\_{123} s\_{14} + s\_{124} s\_{13} \mp
\sqrt{s\_{12}^2 s\_{134}^2 - 2 s\_{12} s\_{123} s\_{134} s\_{14} - 2 s\_{12} s\_{124} s\_{13} s\_{134} + s\_{123}^2 s\_{14}^2 - 2 s\_{123} s\_{124} s\_{13} s\_{14} + s\_{124}^2 s\_{13}^2}}{2 s\_{14} s\_{134}}
$$
</font size>

---

<b> What happens at six point? </b>

Now we have three polynomial scattering equations:

<font size=5>
$$
\mkern-30mu H = \\left(
		\\begin{array}{c}
		h\_1 \\\\\\
		h\_2 \\\\\\
		h\_3 \\\\\\
		\\end{array}
		\\right) = 
\left[\begin{matrix}s\_{12} z\_{2} + s\_{13} z\_{3} + s\_{14} z\_{4} + s\_{15} z\_{5} \\\\ s\_{123} z\_{2} z\_{3} + s\_{124} z\_{2} z\_{4} + s\_{125} z\_{2} z\_{5} + s\_{134} z\_{3} z\_{4} + s\_{135} z\_{3} z\_{5} + s\_{145} z\_{4} z\_{5} \\\\ s\_{1234} z\_{2} z\_{3} z\_{4} + s\_{1235} z\_{2} z\_{3} z\_{5} + s\_{1245} z\_{2} z\_{4} z\_{5} + s\_{1345} z\_{3} z\_{4} z\_{5}\end{matrix}\right]
$$
</font size>

We want to eliminate 4 variables:
<font size=5>
$$
\\{1, z\_2\\} \otimes \\{1, z\_3\\} = \\{1, z\_2, z\_3, z\_2 z\_3\\}
$$
</font size>

But we only have 3 equations:

<font size=5>
$$
\\{h\_1, h\_2, h\_3\\}
$$
</font size>

---

<b> Completing the system of equations </b>

The solution is to introduce new variables and new equations:

<font size=5>
$$
\\{1, z\_3\\} \otimes \\{1, z\_2, z\_3, z\_2 z\_3\\} = \\{1, z\_2, z\_3, z\_2 z\_3, z\_3^2, z\_2 z\_3^2\\}
$$
</font size>

<font size=5>
$$
\\{1, z\_3\\} \otimes \\{h\_1, h\_2, h\_3\\} = \\{h\_1, h\_2, h\_3, z\_3 h\_1, z\_3 h\_2, z\_3 h\_3\\}
$$
</font size>

Now we have the same number of equations and variables, write:

<font size=5>
<p class="fragment">
$$
   	\left(
	\\begin{array}{cc}
	H & H^{z\_2} & H^{z\_3} & H^{z\_2z\_3} & 0 & 0 \\\\\\
	0 & 0 & H & H^{z\_2} & H^{z\_3} & H^{z\_2z\_3} \\\\\\
	\\end{array}
	\\right)\Big|\_{z\_2=0, z\_3=0} \cdot
	\\left(\\begin{array}{c}
	1\\\\\\
	{z\_2}\\\\\\
	{z\_3}\\\\\\
	{z\_2 z\_3}\\\\\\
	{z\_3^2}\\\\\\
	{z\_2 z\_3^2}\\\\\\
	\\end{array}
	\\right) = 0
$$
</p>
</font size>

<font size=2>
<p class="fragment">
$$
$$
$$
\left(\begin{matrix}s\_{14} z\_{4} + s\_{15} z\_{5} & s\_{12} & s\_{13} & 0 & 0 & 0\\\\\\
s\_{145} z\_{4} z\_{5} & s\_{124} z\_{4} + s\_{125} z\_{5} & s\_{134} z\_{4} + s\_{135} z\_{5} & s\_{123} & 0 & 0\\\\\\
0 & s\_{1245} z\_{4} z\_{5} & s\_{1345} z\_{4} z\_{5} & s\_{1234} z\_{4} + s\_{1235} z\_{5} & 0 & 0\\\\\\
0 & 0 & s\_{14} z\_{4} + s\_{15} z\_{5} & s\_{12} & s\_{13} & 0\\\\\\
0 & 0 & s\_{145} z\_{4} z\_{5} & s\_{124} z\_{4} + s\_{125} z\_{5} & s\_{134} z\_{4} + s\_{135} z\_{5} & s\_{123}\\\\\\
0 & 0 & 0 & s\_{1245} z\_{4} z\_{5} & s\_{1345} z\_{4} z\_{5} & s\_{1234} z\_{4} + s\_{1235} z\_{5}\end{matrix}\right) \cdot
	\\left(\\begin{array}{c}
	1\\\\\\
	{z\_2}\\\\\\
	{z\_3}\\\\\\
	{z\_2 z\_3}\\\\\\
	{z\_3^2}\\\\\\
	{z\_2 z\_3^2}\\\\\\
	\\end{array}
	\\right) = 0
$$
</p>
</font size>

---

<b> Problem: the determinant is sextic </b>

<img src="det6.png"; style="max-width:1020px;float:center;border:none;">

Abel–Ruffini theorem: no algebraic solution for order higher than 4.

In general: $\;$ order det $\;\sim\;$ # of SE solutions $\;\sim\;$ $(n-3)!$

---

<b> Solution: use a numerical root-finding algorithm </b>

Two open source packages: [seampy](https://github.com/GDeLaurentis/seampy), [lips](https://github.com/GDeLaurentis/lips)

```python
>>> hms(6)
⎡                     s₁₂⋅z₂ + s₁₃⋅z₃ + s₁₄⋅z₄ + s₁₅⋅z₅                     ⎤
⎢s₁₂₃⋅z₂⋅z₃ + s₁₂₄⋅z₂⋅z₄ + s₁₂₅⋅z₂⋅z₅ + s₁₃₄⋅z₃⋅z₄ + s₁₃₅⋅z₃⋅z₅ + s₁₄₅⋅z₄⋅z₅⎥
⎣     s₁₂₃₄⋅z₂⋅z₃⋅z₄ + s₁₂₃₅⋅z₂⋅z₃⋅z₅ + s₁₂₄₅⋅z₂⋅z₄⋅z₅ + s₁₃₄₅⋅z₃⋅z₄⋅z₅     ⎦
```

```python
>>> oParticles = Particles(6)
>>> num_ss = {str(s): oParticles.compute(str(s)) for s in mandelstams(6)}
```

```python
>>> sols = solve_scattering_equations(6, num_ss)
>>> len(sols)
6
>>> sols[0]
{'z3': mpc(real='#nbr', imag='#nbr'),
 'z4': mpc(real='#nbr', imag='#nbr'),
 'z5': mpc(real='#nbr', imag='#nbr')}
```

---

<b> Recursion for the elimination theory matrix </b>

<br>

<font size=5>
$$
\mkern -24mu M\_i=
  \left(
    \begin{array}{ccccccc}
      M\_{i-1} & M\_{i-1}^{z\_{i-3}} & 0 & \dots & 0 & 0\\\\\\
      0 & M\_{i-1} & M\_{i-1}^{z\_{i-3}} & \dots & 0 & 0\\\\\\
      \vdots & \vdots & \vdots & \ddots & \vdots & \vdots\\\\\\
      0 & 0 & 0 & \dots & M\_{i-1} & M\_{i-1}^{z\_{i-3}}\\\\\\
    \end{array}
  \right), \quad
  M\_4=H, \quad
  H =
  \left(
    \begin{array}{c}
      h\_1\\\\\\
      h\_2\\\\\\
      \vdots\\\\\\
      h\_{n-3}\\\\\\
    \end{array}
  \right)
$$
</font size>

<br>

$M\_i$ is of dimensions $(i−4)×(i−3)$ when written in terms of $M\_{i−1}$.
After a derivative is taken the relevant $z\_i$ is assumed to be set to zero.

</section>
---
---
<section>

# B&nbsp;3. &nbsp;CHY-Integrands

---

<b> Quick recap </b>
<br>

Recall the expression for the amplitudes:

$\textit{A}\_n \, = \, z\_1^4 \cdot i \sum\_{j = 1}^{(n-3)!} \frac{I\_{\scriptscriptstyle CHY}(z^{(j)}(k); k; ϵ)}{\det(ϕ\_{rst}^{ijk})(z^{(j)}(k); k)}$

<br>
So far:

$\circ\mkern -10mu \checkmark$ Theory independent part $z^{(j)}(k)$.

$\circ\mkern -10mu ✗$ Theory dependent part $I\_{\scriptscriptstyle CHY}(z^{(j)}(k); k; ϵ)$.

<br>
First of all, note that $I\_{\scriptscriptstyle CHY}$ must come with <br> four powers of $z_1=\infty$ in the denominator.

---

<b>Summary of considered theories</b>

<br>

<font size=5>

<table width=50% border="1" cellspacing="0" cellpadding="0" style="margin-bottom:-10px">
  <tr class="greenline">
    <td colspan="2", rowspan="2"> <div id="rot90"> <center> <b> $\times $ </b> </center> </div> </td>
    <td colspan="4"> <center> <b> $I_{\scriptscriptstyle CHY}$ </b> </center> </td>
  </tr>
  <tr>
    <td><b>$Pf'(Ψ)$</b></td>
    <td><b>$C_n$</b></td>
    <td><b>$Pf'(A)^2$</b></td>
    <td><b>$W_1$</b></td>
  </tr>
  <tr>
    <td rowspan="4"> <b> $I_{\scriptscriptstyle CHY}$ </b> </td>
    <td><b>$Pf'(Ψ)$</b></td>
    <td>EG</td>
    <td>YM</td>
    <td>BI</td>
    <td>CG</td>
  </tr>
  <tr>
    <td><b>$C_n$</b></td>
    <td>YM</td>
    <td>BS</td>
    <td>NLSM</td>
    <td>$(DF)^2$</td>
  </tr>
  <tr>
    <td><b>$Pf'(A)^2$</b></td>
    <td>BI</td>
    <td>NLSM</td>
    <td>Galileon</td>
    <td>?</td>
  </tr>
  <tr>
    <td><b>$W_1$</b></td>
    <td>CG</td>
    <td>$(DF)^2$</td>
    <td>?</td>
    <td>?</td>
  </tr>
</table>

</font size>
<br>

<font size=5>
Table: Possible QFTs built out of $Pf'(Ψ)$ , $C\_n$ , $Pf'(A)^2$ and $W\_1$.<br>
A product is implied between rows and columns, eg: $I\_{\scriptscriptstyle CHY, EG} = Pf'(Ψ) × Pf'(Ψ)$.
</font size>

---

<b> Definitions (scalars) </b>

<br>

The Parke-Taylor-like factor $C_n$ is defined as:

<font size=5>
$
C_n = \frac{1}{(z_1 - z_2) \dots (z_n - z_1)}
$
</font size>

Theories involving this factor are color ordered.

<br>

The $W_1$ factor from [[29](https://arxiv.org/abs/1707.02192)]:

<font size=5>
$
W\_1 = ∏\_{i \in A} ω_i \;, \quad \text{with} \quad ω\_i = \sum\limits\_{j \in A \backslash \\{i\\}} \frac{ϵ\_i \cdot k\_j \, (z\_j - z\_r)}{(z\_r - z\_i)(z\_i - z\_j)} \;, \;\; r ≠ i.
$
</font size>

---

<b> Definitions (matrices) </b>

<br>

<font size=5>
$$
 \Psi\_{2n\times2n}^{\text{anti-sym.}} =
  \left(
    \begin{array}{cc}
      A\_{n\times n} & -C^T\_{n\times n}\\\\\\
      C\_{n\times n} & B\_{n\times n}
    \end{array}
  \right),
  \quad\quad
  A_{ab} =
  \begin{cases}
    \frac{2 k_a \cdot k_b}{(z_a - z_b)} & a \neq b \; ,\\\\\\
    0 & a = b \; ,
  \end{cases}
$$

<br>

$$
  B\_{ab} =
  \begin{cases}
    \frac{2 ϵ\_a \cdot ϵ\_b}{(z\_a - z\_b)} & a \neq b \; ,\\\\\\
    0 & a = b \; ,
  \end{cases} 
  \quad\quad
  C_{ab} =
  \begin{cases}
    \frac{2 ϵ\_a \cdot k\_b}{(z\_a - z\_b)} & a \neq b \; ,\\\\\\
    - \sum\limits\_{j \in A \backslash \\{a\\}} \frac{2 ϵ\_a \cdot k\_j}{(z\_a - z\_j)} & a = b \; .
  \end{cases}
$$
</font size>

---

<b> The Pfaffian </b>
<br>

The determinant of anti-symmetric matrices can be written as the square of a polynomial.
This polynomial is called the Pfaffian.

<br>

<font size=5>
$
\text{e.g.} \quad A = \left(
\begin{matrix}
0 & a \\\\\
-a & 0
\end{matrix}
\right) \, , \quad
\det(A) = a ^ 2 \, , \quad
\text{Pf}(A) = a
$
</font size>

<br>

Note: non trivial to get the Pfaffian from the determinant, <br> due to sign ambiguity.

---

<b> The reduced Pfaffian </b>
<br>

The matrices $A$ and $\Psi$ have two null vectors, <br> therefore their determinant and Pfaffian are zero.

<br>

Instead use:

<font size=5>
$
\text{Pf'}(\Psi) = \frac{(-1)^{i+j}}{z\_i - z\_j} \text{Pf}(\Psi\_{ij}^{ij}) \; ,
$
</font size>

$\Psi_{ij}^{ij}$ denotes deletion of rows and columns $i$ and $j$.

---

<b> An easy identity to spot </b>

Born-Infeld, non linear sigma model and Galileon amplitudes involve the Pfaffian of the <font size=5>$n\times n$</font size> matrix $A$.

<br>

The Pfaffian of an odd-size matrix is zero, <br> meaning in these theories only even point functions are non-vanishing.

<br>

More specifically, for Born-Infeld amplitudes this is a consequence of helicity conservation.

</section>
---
---
<section>

# 4. Amplitudes

---

<b> Numerical amplitudes </b>
<br>

We now have all the building blocks to compute amplitudes.

<br>

With the open source packages this is straightforward:

```python
>>> from seampy import theories, NumericalAmplitude
>>> from lips import Particles

>>> theories
[YM, EG, BS, BI, NLSM, Galileon, CG, DF2]

>>> oDF2Amp = NumericalAmplitude(theory="DF2", helconf="+++++")
>>> oParticles = Particles(5)

>>> oDF2Amp(oParticles)
mpc(real='#nbr', imag='#nbr')
```

---

<b> Analytical reconstruction </b>
<br>

Using the same strategy previously discussed we can reconstruct analytical expressions. For example:

<font size=4>
$$
\begin{gathered}
    A_{(\text{DF})^2}(1^+,\,2^+,\,3^+,\,4^+,\,5^+) =\\\\\\
    \frac{i[12]⟨13⟩⟨25⟩[35]^2}{⟨12⟩^2⟨34⟩⟨45⟩}+\frac{i[14][24][35]}{⟨12⟩⟨35⟩}+\\\\\\
    (12345 → 23451)\,+\,(12345 → 34512)\,+\\\\\\
    (12345 → 45123)\,+\,(12345 → 51234)\,+\\\\\\
    \frac{2i[15][23]⟨4|1+2|4]}{⟨12⟩⟨34⟩⟨45⟩}+\\\\\\
    \frac{2i[12][45]⟨3|1+5|3]}{⟨15⟩⟨23⟩⟨34⟩}+\\\\\\
    \frac{2i[12][15][34]}{⟨23⟩⟨45⟩}\phantom{+}
\end{gathered}
$$
</font size>

</section>
---
---
<section>

# Summary

---
1) Spinor-helicity rational coefficients can be reconstructed using:

$\circ$ singular limits for to the least common denominator;

$\circ$ doubly singular limits for partial fraction decompositions;

$\circ$ generic ansatze in singular limits for numerators;

Applications involve tree-level, one-loop and two-loop expressions alike.

<br>

2) Amplitudes in the CHY formalism can be computed via:

$\circ$ the scattering equations, numerically solved via elimination theory;

$\circ$ CHY-Integrads, which make manifest relations between theories;

Analytical expressions are then accessible using the above strategy.

---

# Outlook

---

Application to the following quantities is well within reach:

$\circ$ six-parton one-loop amplitudes;

$\circ$ five-parton two-loop amplitudes;

for which we have already reconstructed several components.

<br>

Additionally it might be of interest to:

$\circ$ implement analytical expressions on GPGPU for fast evaluations;

$\circ$ reconstruct the seven-gluon one-loop coefficients;

$\circ$ assemble the NNLO three-jets cross-section;

$\circ$ apply the reconstruction technique to double copy structures.

---

Thank you for your attention!

<br>
<br>
Questions?

</section>
---
