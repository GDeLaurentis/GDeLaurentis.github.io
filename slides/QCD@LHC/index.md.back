---
title: Analytical amplitudes from numerical evaluations
summary: 
authors: ["Giuseppe De Laurentis"]
tags: [QCD, Scattering Amplitudes]
categories: []
date: "2019-02-05T00:00:00Z"
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

# Analytical &nbsp; amplitudes &nbsp; from &nbsp; numerical &nbsp; evaluations

[arXiv:1904.04067](https://arxiv.org/abs/1904.04067)

<br>
Giuseppe De Laurentis

with Daniel Maitre

<br>
QCD@LHC 2019
<br>

IPPP - Durham University

<img src="IP3_logo_blue.png"; style="max-width:280px;float:center;border:none;"> <img src="DurhamLogo.svg"; style="max-width:280px;float:center;border:none;">

{{< speaker_note >}}
- Only speaker can read these.
- Press S to view.
{{< /speaker_note >}}

---

# Table &nbsp;of &nbsp;Contents

<br>

*1. Motivation and introduction*

*2. Singularity structure*

*3. Ansatz and amplitude reconstruction*

*4. Some results (Yang-Mills in the Standard Model)*

---

<section>

# 1.1 &nbsp;Motivation

---

Cross sections at hadron colliders are given by:

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

We can split dynamics from kinematics with the following identities.

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

Brute force calculations are a mess:

<img src="Five_gluons_mess.png"; style="max-width:500px;float:center;border:none;margin-top:-5px;">

Results are often much easier [[6](https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.56.2459),
[7](https://reader.elsevier.com/reader/sd/pii/0550321388904427?token=EFDF378B5E170FFAF0B1BECE184A1EB6304F7798C481CF3C0E7D93DF6D367AE0E093D4D4942C932C66E8BEB75DAB41FE)]:


<font size=5>

$A^{tree}(1^{+}\_{g}2^{+}\_{g}3^{+}\_{g}4^{-}\_{g}5^{-}\_{g}) = \frac{i\,⟨45⟩^{4}}{⟨12⟩⟨23⟩⟨34⟩⟨45⟩⟨51⟩}$

</font size>

---

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
# 1.2 &nbsp;Spinor &nbsp;Helicity

---

The lowest-laying representations of the Lorentz group are:

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

Weyl spinors are sufficient for massless particles:

<font size=5>$\text{det}(P^{\dot\alpha\alpha})=m^2 \rightarrow 0 \quad \Longrightarrow \quad P^{\dot\alpha\alpha} = \bar\lambda^{\dot\alpha}\lambda^\alpha$.</font size>

<br>
In terms of 4-momentum components we have:

<font size=5>$$
\lambda\_\alpha=\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^0+p^3 \\\ p^1+ip^2\end{pmatrix} \, , \;\;\; \lambda^\alpha=\epsilon^{\alpha\beta} \lambda_\beta =\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^1+ip^2 \\\ -p^0+p^3\end{pmatrix}
$$</font size>

<font size=5>$\bar\lambda\_{\dot\alpha}=\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^0+p^3 \\\ p^1-ip^2\end{pmatrix} \, , \;\;\; \bar\lambda^{\dot\alpha}=\epsilon^{\dot\alpha\dot\beta}\bar\lambda_{\dot\beta}=\frac{1}{\sqrt{p^0+p^3}}\begin{pmatrix}p^1-ip^2 \\\ \-p^0+p^3\end{pmatrix}$</font size>

<br>
The left and right Weyl spinors are related by complex conjugation in the case of real momenta, but are independent for complex momenta.

---

Some definitions:

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

</section>
---
---

<section>
# 2.1 &nbsp;Singular &nbsp;limits

---

Singular limits give us information about the poles of the amplitude.

<br>

We need a set of possible poles of the amplitudes:

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


As an example, let us consider the following amplitude:

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
# 2.2 &nbsp;Doubly &nbsp;singular &nbsp;limits

---

Except for the easiest cases, we should really think about $\mathbb{f}$ as:

$\mathbb{f} = \sum\_i \frac{\mathcal{N}_i}{\mathcal{D}_i} = \sum\_i \frac{\mathcal{N}_i}{\mathcal{R}_i\mathcal{S}_i}$,

where $\mathcal{R}\_i$ are products of subsets of $\mathcal{D\_{LCD}}$ (i.e. real poles), <br/> and $\mathcal{S}\_i$ are products of factors not in $\mathcal{D_{LCD}}$ (i.e. spurious poles).

<br>

This information can be accessed by studying doubly singular limits.

We now want phase space points where <u style="text-decoration: underline;
  text-decoration-color: red;"> two invariants vanish</u>:

$r\_i \rightarrow ε \ll 1, \quad r\_j \rightarrow ε \ll 1, \quad \mathbb{f} \rightarrow ε^α \; \Rightarrow \; log(\mathbb{f}) \rightarrow α\cdot log(ε)$

In general we cannot guarantee uniqueness anymore,<br/> even with complex momenta.<br/> $\exists \;r\_{k \neq i, j} \sim \epsilon$.


---

Information from taking the doubly singular limits:

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
      <td>1/30</td>
      <td>1/3</td>
      <td>1/31</td>
      <td>1/2</td>
      <td>2/12</td>
      <td>2/3</td>
      <td>2/10</td>
      <td>1/2</td>
      <td>2/10</td>
    </tr>
    <tr>
      <th>⟨1|6⟩</th>
      <td>1/30</td>
      <td>1</td>
      <td>1/2</td>
      <td>1/2</td>
      <td>1/10</td>
      <td>2/4</td>
      <td>2/12</td>
      <td>1/3</td>
      <td>2/10</td>
      <td>2/10</td>
    </tr>
    <tr>
      <td colspan="11"> <center> $\dots$ </center> </td>
    </tr>
    <tr>
      <th>s_234</th>
      <td>1/2</td>
      <td>2/10</td>
      <td>2/10</td>
      <td>2/10</td>
      <td>2/10</td>
      <td>2/10</td>
      <td>1/2</td>
      <td>2/10</td>
      <td>1</td>
      <td>1/2</td>
    </tr>
    <tr>
      <th>s_345</th>
      <td>2/10</td>
      <td>2/10</td>
      <td>2/10</td>
      <td>1/2</td>
      <td>2/10</td>
      <td>2/10</td>
      <td>2/10</td>
      <td>1/2</td>
      <td>1/2</td>
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


The slope in the doubly singular limit tells us whether two poles should be in the same denominator and the degeneracy how to separate them.

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
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col0" class="data row0 col0" >1/2/2</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col1" class="data row0 col1" >2/10/3</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col2" class="data row0 col2" >2/10/3</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col3" class="data row0 col3" >2/10/3</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col4" class="data row0 col4" >2/10/3</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col5" class="data row0 col5" >2/10/4</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col6" class="data row0 col6" >1/2/2</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col7" class="data row0 col7" >2/10/3</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col8" class="data row0 col8" >1</td> 
        <td id="T_67e20e68_9da2_11e9_b9bf_0242a8af999frow0_col9" class="data row0 col9" >1/2/2</td> 
    </tr></tbody> 
</table>

</font size>

<img src="Graph.gv.svg"; style="max-width:720px;float:center;border:none;margin-bottom:-30px;">

<font size=5> Diagramatic representation of relation between poles</font size>

---

Let us briefly consider the coefficient of a three mass triangle:

<img src="three_mass_triangle.svg"; width=25%; height=25%; style="float:center;border:none;margin-bottom:0px;">

$\mathcal{D\_{LCD}} = ⟨12⟩[12]⟨34⟩[34]⟨56⟩[56]⟨1|3+4|2]^4⟨3|1+2|4]^4⟨5|1+2|6]^4Δ_{135}^3$

<font size=4>

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
      <td>1/2</td>
      <td>1/2</td>
      <td>2/12</td>
      <td>1/2</td>
      <td>2/12</td>
      <td>4/4</td>
      <td>5/6</td>
      <td>2/10</td>
      <td>2/4</td>
    </tr>
    <tr>
      <td colspan="11"> <center> $\dots$ </center> </td>
    </tr>
    <tr>
      <th>⟨3|1+2|4]</th>
      <td>5/6</td>
      <td>2/10</td>
      <td>4/4</td>
      <td>4/4</td>
      <td>2/10</td>
      <td>5/6</td>
      <td>4/2</td>
      <td>4</td>
      <td>4/2</td>
      <td style="background:yellow">3.5/4</td>
    </tr>
    <tr>
      <td colspan="11"> <center> $\dots$ </center> </td>
    </tr>
  </tbody>
</table>

</font size>

Do we need square roots of momentum invariants?

---

All branch cuts should have been taken care of by unitarity cuts.

We should be able to explain this without using square roots.

<br>
The culprit is $\Delta$, which first appears in the <br/> three mass triangle momentum parametrisation:

<font size=5>$\Delta\_{135} = (K\_1 \cdot K\_2)^2 - K\_1^2 K\_2^2$</font size>

<br>
Solution:<br/>
In some limits $\Delta$ behaves like the square of some quantity

<font size=5 style="margin-left:-50px;">$(\Omega\_{351})^2 \equiv (2s\_{12}s\_{56}-(s\_{12}+s\_{56}-s\_{45})s\_{123})^2 = 4s\_{123}^2\Delta\_{135}-4s\_{12}s\_{56}\langle 4|1+2|3]\langle 3|1+2|4]$</font size>

<font size=5>$(\Pi\_{351})^2 \equiv (s\_{123}-s\_{124})^2 = 4\Delta\_{135}-4\langle 4|1+2|3]\langle 3|1+2|4]$</font size>

</section>
---
---

<section>
# 3.1 &nbsp;Partial &nbsp;fraction &nbsp;decomposition

---

Going back to our tree level example,<br/> let's see how we can group together the poles of the amplitude.

<table width=100% border="1" frame="void" cellspacing="0" cellpadding="0">
  <tr class="greenline">
    <td> <center> <img src="Graph2.gv.svg"; style="max-width:540px;float:center;border:none;"> </center> </td>
    <td>
      <center>
        <font size=6>
	  $\frac{\mathcal{N_1}}{[16]⟨23⟩⟨34⟩[56]⟨2|1+6|5]s_{234}}+\\
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
# 3.2 &nbsp;Fitting &nbsp;of &nbsp;ansatz

---

Let's consider the first representation:

$\mathbb{f}=$
$\frac{\mathcal{N\_1}}{[16]⟨23⟩⟨34⟩[56]⟨2|1+6|5]s\_{234}}+$
$\frac{\mathcal{N\_2}}{⟨12⟩⟨16⟩[34][45]⟨2|1+6|5]s\_{345}}$

<br>
$\mathcal{N\_1}$ has mass dimension: 6, and phase weights: [-3, 0, 0, 3, 0, 0].<br/>
We generate all possible products of spinor products compatible with this infomation. The ansatz has size 10:

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

We want to isolate the first term in

$\mathbb{f}=$
$\frac{\mathcal{N\_1}}{[16]⟨23⟩⟨34⟩[56]⟨2|1+6|5]s\_{234}}+$
$\frac{\mathcal{N\_2}}{⟨12⟩⟨16⟩[34][45]⟨2|1+6|5]s\_{345}}$

this can be done by generating phase space points <br/> in the limit of, say, $s_{234} \rightarrow \epsilon$.

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
# 4.1 &nbsp;Application &nbsp;and &nbsp;Results

---

As an application we obtained analytical expressions for all parts of the six-gluon amplitude with a gluon in the loop.

<br>
All independent coefficients are available as anchillary files at: [arXiv:1904.04067](https://arxiv.org/abs/1904.04067).

<br>
These expression were already present in the litterature, but with different structures. We did not use any information from those papers for the reconstruction.

<br>
For a summary of the litterature see Ref.[15](https://arxiv.org/pdf/0901.1202.pdf).

---

For the three mass triangle mentioned in an earlier section, which was previously obtained in [[16](https://arxiv.org/pdf/hep-ph/0602178.pdf)], the poles are:

<font size=5>$\mathcal{D\_{LCD}} = ⟨12⟩[12]⟨34⟩[34]⟨56⟩[56]⟨1|3+4|2]^4⟨3|1+2|4]^4⟨5|1+2|6]^4Δ_{135}^3$</font size>

<table width=90% border="1" frame="void" cellspacing="0" cellpadding="0">
  <tr class="greenline">
    <td> <center> <img src="Graph5.gv.svg"; style="max-width:360px;float:center;border:none;"> </center> </td>
    <td>
      <center>
        <font size=5>
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

We obtain an explicitly rational expression, like for $\mathcal{N}=1$ SUSY in [[17](https://arxiv.org/pdf/0709.2086.pdf)].

---

<iframe src="https://arxiv.org/src/1904.04067v3/anc/AllOneLoop6Gluons/6g_pmpmpm_G/triangle_19_.pdf&embedded=true" style="width:718px; height:700px;" frameborder="0"></iframe>


---

Another interesting piece is the rational part:

<font size=5>
$R^{1-loop}_6(1^{+}\_{g}2^{-}\_{g}3^{+}\_{g}4^{-}\_{g}5^{+}\_{g}6^{-}\_{g})$
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

The pole structure is a bit of a mess:

<img src="GraphRational.gv.svg"; style="maxwidth:1000px; float:center; border:none;">

---

<iframe src="https://arxiv.org/src/1904.04067v3/anc/AllOneLoop6Gluons/6g_pmpmpm_G/rational.pdf&embedded=true" style="width:718px; height:700px;" frameborder="0"></iframe>

</section>
---
---
<section>

# 4.2 &nbsp;Conclusions

---

The aim of this talk was to show that it is possible to reconstruct an analytical expression from numerical evaluations only.

<br>
We discussed a general framework to perform these operations, <br/>
and strategies to tame the complexity of the problem.

<br>
The application given as an example is representative of the complexity of high multiplicity processes and demonstrates the viability of this approach.

<br>
Outlook:<br/>
We have now almost finished reconstructing the six-gluon one-loop amplitude with a fermion loop, and we are considering applications to processes with external quarks and photons, as well as to coefficients of two-loop integrals.

---

Thank you very much!

<br>
<br>
Questions?

</section>
---