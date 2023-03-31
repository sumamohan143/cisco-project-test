#!/bin/bash

# Get the input number from the Jenkins job parameter
num=$1

# Check if the number is a prime number
is_prime=true
if [ $num -le 1 ]; then
    is_prime=false
else
    for ((i=2; i<=num/2; i++)); do
        if [ $((num%i)) -eq 0 ]; then
            is_prime=false
            break
        fi
    done
fi

# Print the result
if [ $is_prime = true ]; then
    echo "$num is a prime number."
else
    echo "$num is not a prime number."
fi
