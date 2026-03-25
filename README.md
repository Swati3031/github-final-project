# Simple Interest Calculator

This project calculates simple interest.

## Formula
Simple Interest = (P × R × T) / 100

## Example Code

principal = float(input("Enter principal: "))
rate = float(input("Enter rate: "))
time = float(input("Enter time: "))

si = (principal * rate * time) / 100

print("Simple Interest:", si)
