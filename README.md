# PCOS-Detection

## Introduction

![image](https://user-images.githubusercontent.com/71822090/128054271-9ab7e120-dde0-4160-957d-84cb1d338fba.png)


Polycystic Ovary Syndrome is a hormonal disorder common among women of reproductive age. Women with PCOS may have infrequent or prolonged menstural periods or excess male hormone levels. The ovaries may develop  small collections of fluid and fail to regularly release eggs.
Due to its wide range of symptoms and the presence of a variety of gynaecological problems, PCOS is extremely difficult to diagnose. The time and money spent on several of the clinical testing and ovarian scans has become a hardship for PCOS patients.

This Machine Learning model aids in the early detection and prediction of PCOS based on a set of ideal and minimal but promising clinical and metabolic indicators that serve as early markers for the syndrome.

## Dataset



It contains all physical and clinical parameters to determine PCOS and infertility related issues.

      
![image](https://user-images.githubusercontent.com/71822090/128052774-06a0d24e-39fa-46ee-8cb3-9e482f316a2d.png)

![image](https://user-images.githubusercontent.com/71822090/128052817-7fc168da-56c3-4ae2-a389-ce4029cf99e5.png)


## Data Cleaning

Missing values were dropped.

Feature Extraction based on Weight of Evidence (WOE) and Information Value (IV).

Extracted Features :

Endometrium (mm)

Weight gain (Y/N)

Hair growth (Y/N)

Cycle (R/I)

Follicle No. ( R )

Follicle No. ( L )

Pimples (Y/N)

Average. F size (L) (mm)

Average. F size ( R )  (mm)

Waist : Hip Ratio

Skin darkening (Y/N)

Further we removed the variables which has  p value > 0.05

Final Features :

Follicle No. ( R )

Follicle No. ( L )

Skin darkening (Y/N)

Hair growth (Y/N)

Weight gain (Y/N)

Cycle (R/I)

Pimples (Y/N)

Age (Yrs)

## Data Modelling

Logistic Regression
The model uses Logistic Regression for the detection and prediction of PCOS.
![image](https://user-images.githubusercontent.com/71822090/128053999-c604712d-ff4f-42e8-beec-d5c2c02ac83c.png)


![image](https://user-images.githubusercontent.com/71822090/128054039-bf284155-50d1-48aa-8c5c-646449fca795.png)


![image](https://user-images.githubusercontent.com/71822090/128054080-83dd564b-c982-4109-877e-36d7065c9fa0.png)

## Conclusion

This could be expanded to make a PCOS prediction application which will help females in constantly checking their health and also can be modified to monitor their food habbits and workouts, and finally could be a better health companion to all women.



