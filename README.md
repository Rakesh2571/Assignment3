using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using NUnit.Framework;
using AwesomeCalculator;

namespace ClassLibrary1
{
    [TestFixture]
    public class Class1
    {

        [Test]
        public void GetAddition_Input1and1_expectedSumEquals2()
        {

            //Arrange

            int a = 1;
            int b = 1;
            double actualsum = a + b;
            Calc objc = new Calc(a,b);

            //Act

            double expectedsum = objc.GetAddition();

            //Assert

            Assert.AreEqual(actualsum, expectedsum);

        }

        [Test]
        public void GetAddition_Input2and2_expectedSumEquals4()
        {

            //Arrange

            int a = 2;
            int b = 2;
            double actualsum = a + b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedsum = objc.GetAddition();

            //Assert

            Assert.AreEqual(actualsum, expectedsum);

        }

        [Test]
        public void GetAddition_Input3and3_expectedSumEquals6()
        {

            //Arrange

            int a = 3;
            int b = 3;
            double actualsum = a + b; 
            Calc objc = new Calc(a, b);

            //Act

            double expectedsum = objc.GetAddition();

            //Assert

            Assert.AreEqual(actualsum, expectedsum);

        }

        [Test]
        public void GetSubtraction_Input5and1_expectedSubtractionEquals1()
        {

            //Arrange

            int a = 5;
            int b = 1;
            double actualsubtraction = a - b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedsubtraction = objc.GetSubtraction();

            //Assert

            Assert.AreEqual(actualsubtraction, expectedsubtraction);

        }

        [Test]
        public void GetSubtraction_Input6and2_expectedSubtractionEquals4()
        {

            //Arrange

            int a = 6;
            int b = 2;
            double actualsubtraction = a - b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedsubtraction = objc.GetSubtraction();

            //Assert

            Assert.AreEqual(actualsubtraction, expectedsubtraction);

        }

        [Test]
        public void GetSubtraction_Input7and2_expectedSubtractionEquals5()
        {

            //Arrange

            int a = 7;
            int b = 2;
            double actualsubtraction =  a - b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedsubtraction = objc.GetSubtraction();

            //Assert

            Assert.AreEqual(actualsubtraction, expectedsubtraction);

        }

        [Test]
        public void GetMultiplication_Input1and1_expectedMultiplicationEquals1()
        {

            //Arrange

            int a = 1;
            int b = 1;
            double actualmultiplication = a * b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedmultiplication = objc.GetMultiplication();

            //Assert

            Assert.AreEqual(actualmultiplication, expectedmultiplication);

        }

        [Test]
        public void GetMultiplication_Input1and1_expectedMultiplicationEquals2()
        {

            //Arrange

            int a = 2;
            int b = 1;
            double actualmultiplication = a * b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedmultiplication = objc.GetMultiplication();

            //Assert

            Assert.AreEqual(actualmultiplication, expectedmultiplication);

        }

        [Test]
        public void GetMultiplication_Input4and1_expectedMultiplicationEquals4()
        {

            //Arrange

            int a = 4;
            int b = 1;
            double actualmultiplication = a * b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedmultiplication = objc.GetMultiplication();

            //Assert

            Assert.AreEqual(actualmultiplication, expectedmultiplication);

        }

        [Test]
        public void GetDivision_Input4and2_expectedDivisionEquals2()
        {

            //Arrange

            int a = 4;
            int b = 2;
            double actualDivision = a / b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedDivision = objc.GetDivision();

            //Assert

            Assert.AreEqual(actualDivision, expectedDivision);

        }

        [Test]
        public void GetDivision_Input6and2_expectedDivisionEquals3()
        {

            //Arrange

            int a = 6;
            int b = 2;
            double actualDivision = a / b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedDivision = objc.GetDivision();

            //Assert

            Assert.AreEqual(actualDivision, expectedDivision);

        }

        [Test]
        public void GetDivision_Input8and2_expectedDivisionEquals4()
        {

            //Arrange

            int a = 8;
            int b = 2;
            double actualDivision = a / b;
            Calc objc = new Calc(a, b);

            //Act

            double expectedDivision = objc.GetDivision();

            //Assert

            Assert.AreEqual(actualDivision, expectedDivision);

        }
    }
}
