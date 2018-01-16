# Stay Positive attribute for Unity

Add the [StayPositive] tag in front of a variable and the editor won't let it become a negative number.

Works for float, int, vector2, vector3 and vector4.

```
[StayPositive] public float positiveFloat = 1;
[StayPositive] public int positiveInt = 1;
[StayPositive] public Vector3 positiveVector = Vector3.one;
```

# Installation
Copy this anywhere in your Unity project (that's not an Editor folder).
