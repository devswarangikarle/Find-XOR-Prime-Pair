# Find-XOR-Prime-Pair

Alex is given a non-negative integer A, and his friend Ravi challenges him to find another non-negative integer B such that the XOR of A and B results in an even prime number. In other words, the result of A XOR B should yield an even prime. Can you help Alex determine such an integer B?

def find_xor_prime_pair(A):

    # Compute B such that A XOR B = 2
    B = A ^ 2
    return B

# Input
A = int(input())
# Output the result
print(find_xor_prime_pair(A))
