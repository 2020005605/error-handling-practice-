# import pytest

def test_divide_by_zero():
    with pytest.raises(ZeroDivisionError):
        result = 1 / 0
        
