https://medium.com/@tommy_chan/eip-4844-proto-danksharding-using-kzg-commitment-what-it-does-and-how-does-it-really-work-35201987b24c

The prover needs to provide an Opening Triplets (OT) = (z, f(z), Cₕ) to the verifier. z is chosen by verifier, f(z) can be easily computed as prover has the polynomial, but what is Cₕ?
We start with f(x) — f(z)
f(z) — f(z) = 0, we know x = z must be a root, so there exists h(x) such that
f(x) — f(z) = (x-z) * h(x)
h(x) = (f(x) — f(z)) / (x-z)
