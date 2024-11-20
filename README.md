a .b = Σ(aᵢ × bᵢ)

def dot_product(vector1, vector2):
    return sum(a * b for a, b in zip(vector1, vector2))

![Vector Diagram](https://example.com/vector-diagram.png)

| Algorithm Version | Time Complexity | Space Complexity |
|-------------------|-----------------|------------------|
| Naive             | O(n)            | O(1)             |
| Optimized         | O(n)            | O(1)             |
