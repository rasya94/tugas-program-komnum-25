
# Tugas Program KomNum

**NRP:** 5025241239
**Nama:** Rasya Nur Aqilla

### Rumus Metode Secant  
![Secant Formula](https://math.now.sh?from=x_%7Bi%2B1%7D%20%3D%20x_i%20-%20%5Cfrac%7Bf%28x_i%29%20%28x_%7Bi-1%7D%20-%20x_i%29%7D%7Bf%28x_%7Bi-1%7D%29%20-%20f%28x_i%29%7D)

![Secant Formula](https://latex.codecogs.com/png.latex?%5Cdpi%7B150%7D%20%5Ccolor%7Bwhite%7D%20x_%7Bi%2B1%7D%20%3D%20x_i%20-%20%5Cfrac%7Bf%28x_i%29%28x_%7Bi-1%7D%20-%20x_i%29%7D%7Bf%28x_%7Bi-1%7D%29%20-%20f%28x_i%29%7D)

- **Code**
	 ```py
	 cx = x1 - fx(x1) * (xo - x1) / (fx(xo) - fx(x1))
	 cx = round(cx, 2)
	 ```

### Rumus Et  
![Et Formula](https://math.now.sh?from=E_t%20%3D%20%5Cfrac%7Bx_%7B%5Ctext%7Basli%7D%7D%20-%20x_i%7D%7Bx_%7B%5Ctext%7Basli%7D%7D%7D)

![Et Formula](https://latex.codecogs.com/png.latex?%5Cdpi%7B150%7D%20%5Ccolor%7Bwhite%7D%20E_t%20%3D%20%5Cfrac%7Bx_%7Basli%7D%20-%20x_i%7D%7Bx_%7Basli%7D%7D)

 - **Code**
	 ```py
	 Et = abs((xa - cx) / xa * 100)
	 Et = round(Et, 2)
	 ```

### Rumus Ea  
![Ea Formula](https://math.now.sh?from=E_a%20%3D%20%5Cfrac%7Bx_%7Bi-1%7D%20-%20x_i%7D%7Bx_%7Bi-1%7D%7D)

![Ea Formula](https://latex.codecogs.com/png.latex?%5Cdpi%7B150%7D%20%5Ccolor%7Bwhite%7D%20E_a%20%3D%20%5Cfrac%7Bx_%7Bi-1%7D%20-%20x_i%7D%7Bx_%7Bi-1%7D%7D)

  - **Code**
	 ```py
	 Ea = abs((cx - cprev) / cx * 100)
	 Ea = round(Ea, 2)
	 ```
