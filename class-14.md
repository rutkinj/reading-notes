# Reading

## Password Hashing

- bad idea: sotre password as cleartext, no encrypt
- plaintext -> data to input into cryptograph
- plain text -> plain ol' text
- en/decryption -> alter text based on a key and later change it back using same key
- hashing -> alter text of any length into random garbage of a fixed length that can't be easily changed back?
- pre-image -> plaintext?
- hashing is deterministic, specific input always produces the same output. This is why you can use it for passwords. Set your password -> hashed -> result is saved. Enter password -> hashed -> compare to stored hash. cool.
- hashing is slow on purpose
- hashing algorithms depricate

## bcrypt bcuz gud

- this article is bad
- bcrypt is the best because of Key Factor

## bcrypt docs

- i'm no expert but the code example looks like it's just salting the pw?
- hashed salt maybe??
