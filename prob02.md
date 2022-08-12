# Second Problem

## Author: Đặng Đình Đức

### Date: Friday, August 12, 2022

$$ A = \left(\frac{3x + \sqrt{16x}-7}{x + 2\sqrt{x}-3} -\frac{\sqrt{x}+1}{\sqrt{x} + 3}-\frac{\sqrt{x}+7}{\sqrt{x}-1}\right) \colon \left(2 - \frac{\sqrt{x}}{\sqrt{x}-1}\right)  $$

> Well đối với các dạng bài giống như thế này chúng ta thường quan tâm đến mẫu số. \
> Và ở đây $x + 2\sqrt{x}-3$ \
> Và dễ thấy rằng $\left(\sqrt{x} + 3\right)\cdot\left(\sqrt{x}-1\right)=x+3\sqrt{x}-\sqrt{x}-3=x + 2\sqrt{x}-3$ \
> Nên ở đây chúng ta sẽ lấy mẫu số chung là $\left(\sqrt{x} + 3\right)\left(\sqrt{x}-1\right)$

$$ A = \left(\frac{\left(3x + \sqrt{16x}-7\right)-\left(x-1\right)-\left(\left(\sqrt{x}+7\right)\left(\sqrt{x}+3\right)\right)}{\left(\sqrt{x} + 3\right)\left(\sqrt{x}-1\right)}\right) \colon \left(2 - \frac{\sqrt{x}}{\sqrt{x}-1}\right)  $$


> $\left(\sqrt{x}+7\right)\left(\sqrt{x}+3\right)=x+10\sqrt{x}+21$ 

$$ A = \left(\frac{3x + \sqrt{16x}-7-x+1-x-10\sqrt{x}-21}{\left(\sqrt{x} + 3\right)\left(\sqrt{x}-1\right)}\right) \colon \left(2 - \frac{\sqrt{x}}{\sqrt{x}-1}\right)  $$

> $3x + \sqrt{16x}-7-x+1-x-10\sqrt{x}-21=x+4\sqrt{x}-10\sqrt{x}-27=x+6\sqrt{x}-27$ \
> $x+6\sqrt{x}-27$ vẫn còn hơi xấu đúng chứ \
> Vậy nên chúng ta cần tách nó ra \
> $x+6\sqrt{x}-27=x+3\sqrt{x}-9\sqrt{x}-27=\left(\sqrt{x}\right)\left(\sqrt{x}+3\right)\cdot\left(-9\right)\left(\sqrt{x}+3\right)=\left(\sqrt{x}-9\right)\left(\sqrt{x}+3\right)$

$$ A = \left(\frac{\left(\sqrt{x}-9\right)\left(\sqrt{x}+3\right)}{\left(\sqrt{x} + 3\right)\left(\sqrt{x}-1\right)}\right) \colon \left(2 - \frac{\sqrt{x}}{\sqrt{x}-1}\right)  $$

> Triệt tiêu $\sqrt{x}+3$

$$ A = \left(\frac{\sqrt{x}-9}{\sqrt{x}-1}\right) \colon \left(2 - \frac{\sqrt{x}}{\sqrt{x}-1}\right)  $$

> well giờ chúng ta sẽ xử lý $2 - \frac{\sqrt{x}}{\sqrt{x-1}}$

$$2 - \frac{\sqrt{x}}{\sqrt{x-1}} = \frac{2\sqrt{x}-2-\sqrt{x}}{\sqrt{x}-1}=\frac{\sqrt{x}-2}{\sqrt{x}-1} $$

> Thay vào thôi
$$ A = \left(\frac{\sqrt{x}-9}{\sqrt{x}-1}\right) \colon \left(\frac{\sqrt{x}-2}{\sqrt{x}-1}\right)  $$

$$ A = \left(\frac{\sqrt{x}-9}{\sqrt{x}-1}\right) \cdot \left(\frac{\sqrt{x}-1}{\sqrt{x}-2}\right)  $$

> Triệt tiêu $\sqrt{x}-1$

$$ A = \frac{\sqrt{x}-9}{\sqrt{x}-2}  $$

> Thế là xong phần a rồi đấy

Ta có $A=-6$

> Suy ra: 

$$ \frac{\sqrt{x}-9}{\sqrt{x}-2} = -6 $$
$$ \sqrt{x} - 9 = -6\sqrt{x}+12 $$
$$ 7\sqrt{x} = 21 $$
$$ \sqrt{x} = 3 $$
$$ x = 9 $$

> Thế là xong