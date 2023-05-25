# Yukawa couplings with spontaneous symmetry breaking (SSB)

![Python package](https://github.com/zaaahir/yukawa/workflows/Python%20package/badge.svg)
![Upload Python Package](https://github.com/zaaahir/yukawa/workflows/Upload%20Python%20Package/badge.svg)

Given a list of integers as the Abelian charges of fermions, check if there is a scalar which which can generate Yukawa couplings and non-zero masses for all them after the SSB-

## Usage

```python
>>> from yukawa import yukawa
>>> yukawa.get_massive_fermions([2, 4, 4, 5, 5, 7],9)
{'S': 9, 'ψ': [(2, 7), (4, 5)]}
```
