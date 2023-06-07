# 复数类实现
```cpp
template<typename T>

class Complex{

public:
	T re,im;
	
	Complex(T _re,T _im):re(_re),im(_im){};
	Complex(T _re):Complex(_re,0) {};
	Complex():Complex(0,0) {};
	Complex(const Complex &_c) {re=_c.re;im=_c.im;} ;
	
	Complex(std::initializer_list<T> lst):
	re(lst.begin()[0]),im(lst.begin()[1]) {};
	
	friend std::ostream & operator<<(std::ostream &out,
	const Complex &_c){
		out<<_c.re<<'+'<<_c.im<<"j";
		return out;
	};
	
	Complex operator +(const Complex &_c) const{
		return Complex(re+_c.re,im+_c.im);
	};
	
	Complex operator -(const Complex &_c) const{
		return Complex(re-_c.re,im-_c.im);
	};
	
	Complex operator *(const Complex &_c) const{
		return Complex(re*_c.re-im*_c.im,re*_c.im+im*_c.re);
	}
	
	Complex operator *(const double &sc) const{
	
	return Complex(re*sc,im*sc);
	
	}
	
	  
	
	Complex operator /(const Complex &_c) const{
	
	return Complex((re*_c.re+im*_c.im)/(_c.im*_c.im+_c.re*_c.re),(im*_c.re-re*_c.im)/(_c.im*_c.im+_c.re*_c.re));
	
	}

};

  

template<typename T>

Complex<T> operator*(const double &sc,const Complex<T> &_c){

return Complex<T>(sc*_c.re,sc*_c.im);

}
```