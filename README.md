**RSA-Breaker**

RSA-Breaker is a command-line tool that extracts the modulus from an RSA public key, factors it into two primes, and generates the corresponding private key. The tool provides colored logging output to track the process and detect potential issues.

**Features**

    Extract Modulus: Extracts the modulus (n) from an RSA public key.
    Factorization: Factors the modulus into its prime components (p and q).
    Private Key Generation: Computes the private key and saves it in PEM format.
    Colored Logging: Provides colored logging output for easy tracking and debugging.


 **Usage**

    ./RSA-Breaker --key-file public_key.pem --output-file private_key.pem
