#  Single Responsiblity Principle

- Giả sử chúng ta đang xây dựng tính 
```
class Circle
{
    public $radius;

    public function __construct($radius)
    {
        $this->radius = $radius;
    }
}

class Square
{
    public $length;

    public function __construct($length)
    {
        $this->length = $length;
    }
}

class AreaCalculator
{
    public $shapes;

    public function __construct(array $shapes)
    {
        $this->shapes = $shapes;
    }

    public function sum()
    {
        // Thực hiện logic tính tổng diện tích các hình
    }

    public function output()
    {
        echo 'Sum: <b>' . $this->sum() . '</b>';
    }
}

$shapes = [
    new Circle(2),
    new Square(5)
];
$areaCalculator = new AreaCalculator($shapes);

$areaCalculator->output();
```
