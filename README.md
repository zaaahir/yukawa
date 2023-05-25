# Yukawa couplings with spontaneous symmetry breaking (SSB)


Given a list of integers as the Abelian charges of fermions, check if there is a scalar which which can generate Yukawa couplings and non-zero masses for all them after the SSB-

## Usage

```python
>>> from yukawa import yukawa
>>> yukawa.get_massive_fermions([2, 4, 4, 5, 5, 7],9)
{'S': 9, 'ψ': [(2, 7), (4, 5)]}
```
