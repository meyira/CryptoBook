# Mathematical Notation

## Introduction

Throughout CryptoBook, discussions are made more concise by using various mathematical symbols. For some of you, all of these will feel familiar, while for others, it will feel new and confusing. This chapter is devoted to helping new readers gain insight into the notation used.

{% hint style="info" %}
If you're reading a page and something is new to you, come here and add the symbol, someone else who understands it can explain its meaning
{% endhint %}

## Mathematical Objects

### Special Sets

* $$\mathbb{C}$$: denotes the set of complex numbers
* $$\mathbb{R}$$: denotes the set of real numbers
* $$\mathbb{Z}$$: denotes the set of integers
* $$\mathbb{Q}$$: denotes the set of rational numbers
* $$\mathbb{N}$$: denotes the set of natural numbers \(non-negative integers\)

```python
# We can call each of these sets with Sage using the following:
sage: CC
Complex Field with 53 bits of precision
sage: RR
Real Field with 53 bits of precision
sage: ZZ
Integer Ring
sage: QQ
Rational Field
sage: NN
Non negative integer semiring
```

* We refer to a general field by $$k$$
* We refer to the algebraic closure of this field by $$\bar{k}$$

```python
# Example of defining a field and then its 
# algebraic closure
sage: k = GF(3); k
Finite Field of size 3
sage: k_bar = k.algebraic_closure(); k_bar
Algebraic closure of Finite Field of size 3
```

### Relation operators

* $$\in$$means is an element of

### Logical Notation

* $$\forall$$means for all
* $$\exists$$means there exists


