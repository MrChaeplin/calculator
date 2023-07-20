# Lv 2. calculator

class Calculator {
     var result: Double = 0

    func add(_ number1: Double, _ number2: Double) -> Double {
        result = number1 + number2
        return result
    }

    func substract(_ number1: Double, _ number2: Double) -> Double {
        result = number1 - number2
        return result
    }

    func multiply(_ number1: Double, _ number2: Double) -> Double {
        result = number1 * number2
        return result
    }

    func divide(_ number1: Double, _ number2: Double) -> Double {
        if number2 != 0 {
            result = number1 / number2
            return result
        } else {
            return result
        }
    }

    func remainder(_ number1: Int, _ number2: Int) -> Int {
        if number2 != 0 {
            return number1 % number2
        } else {
            return 0
        }
    }
}

var getResult = Calculator()
getResult.add(60, 40)
getResult.substract(65, 12) 
getResult.multiply(30, 30) 
getResult.divide(50, 5)
getResult.remainder(20, 3)


