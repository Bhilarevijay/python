# python

This repo contains some basic concepts of python and data processing.
There are also some practice assignments to try.

Practice assignments :-

1. Perform Linear Regression on the following dataset. (dataset = train.xlsx) #(Linear regression)
   
2. Perform Linear Regression on the given student dataset to predict performance index. (dataset = Student_Performance.xlsx) #(Linear regression)

3. Description of dataset: #(Logistic Regression)# (dataset = farmingham.xlsx)

    Variables
    Each attribute is a potential risk factor. There are both demographic, behavioral and medical risk factors.
   
    Demographic:
    • Sex: male or female(Nominal)
    • Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
   
    Behavioral
    • Current Smoker: whether or not the patient is a current smoker (Nominal)
    • Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
   
    Medical( history)
    • BP Meds: whether or not the patient was on blood pressure medication (Nominal)
    • Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
    • Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
    • Diabetes: whether or not the patient had diabetes (Nominal)
   
    Medical(current)
    • Tot Chol: total cholesterol level (Continuous)
    • Sys BP: systolic blood pressure (Continuous)
    • Dia BP: diastolic blood pressure (Continuous)
    • BMI: Body Mass Index (Continuous)
    • Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
    • Glucose: glucose level (Continuous)
   
    Predict variable (desired target)
    • 10 year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”)

5. Create a 1D tensor in Python using NumPy that contains the numbers from 1 to 10. Then, reshape it into a 2D tensor with 5 rows and 2 columns.

      Write a Python program that creates a 3D tensor using NumPy, where the shape of the tensor is (2, 3, 4), and all elements are initialized to random integers between 0 and 9.
      Using TensorFlow, create a tensor with shape (3, 3) and initialize it with ones. Perform the following operations on it:
      
          Add a scalar value of 5 to all elements.
          Multiply the tensor by a scalar value of 3.
      
      Write a function that takes two 2D tensors as input, and returns their dot product using TensorFlow. 
      Provide a sample input and output.Using NumPy, create two 2D tensors with shapes (3, 2) and (2, 3) and perform matrix multiplication between them.
      
      Write a Python function that takes a 3D tensor and slices it to extract the first 2 rows, all columns, and the last depth slice.Using TensorFlow, create a tensor of shape (4, 4) filled with zeros.
      Then, concatenate this tensor with another tensor of shape (4, 4) filled with ones along the first axis (rows).
      
      Write a Python program to create a zero tensor of shape (5, 5) using TensorFlow. 
      Then, slice the middle 3x3 part of the tensor and assign a value of 1 to all elements in the slice.Using NumPy, create a 2D tensor with shape (4, 4) and perform the following operations:
      
          Subtract a scalar value of 3 from all elements.
          Reshape the tensor into shape (2, 8).
      
      Using TensorFlow, create a tensor with shape (2, 2) containing random integers. Perform element-wise subtraction between this tensor and a scalar value of 3, and print the resulting tensor.
