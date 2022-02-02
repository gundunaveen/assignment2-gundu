# assignment2-gundu

# Naveen Kumar Gundu

###### Hyderabad

Hyderabad is the capital and **largest city** of the Indian state of Telangana.Its historic sites include **Golconda Fort**, a former diamond-trading center that was once the Qutb Shahi dynastic capital.

------------------------------------------------------------------------------

# Rajiv Gandhi International Airport Route Map

### RGI Aiport is the closest running airport to my food location.

1. Catch a Pushpakavimanam bus from RGI Airport.
    1. Take a ticket to Secundrabad.
    2. Catch a bus from Secundrabad to Paradise.
    3. From Paradise walk for 100 meters to reach Paradise Restaurant.
* Chicken Dum Biryani(Double Masala)
* Shawarma with extra cheese
* Spicy Pepper Chicken

[About Me](AboutMe.md)

-----------------------------------------------------------------------------

### Recommended Sports

The below table shows the recommended sports, location and the amount of personal equipment.

|     Sport     |     Location     |     Amount(INR)     |
|---------------|------------------|---------------------|
|    Cricket    |  Cricket Ground  |         1000        |
|   Badminton   |  Badminton Court |         1500        |
|  Volley Ball  | Volley Ball Court|         1000        |
|   Foot Ball   | Foot Ball Court  |         5000        |

----------------------------------------------------------------------------

### Favourite Quotes

> Man is made by his belief. As he believes, so he is. - *Lord Shri Krish*
> There is no other spiritual teacher than your own soul. - *Swamy Vivekananda*

-------------------------------------------------------------------------------

### Code Fencing

> If the polygon can be drawn on an equally spaced grid such that all its vertices are grid points, Pick's theorem gives a simple formula for the polygon's area based on the numbers of interior and boundary grid points: the former number plus one-half the latter number, minus 1.

```
double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}

```
[Source Code](https://en.wikipedia.org/wiki/Polygon#:~:text=If%20the%20polygon%20can%20be,the%20latter%20number%2C%20minus%201.)

