# Code Standards

Install the JHU code standard by running the following command:

```bash
ln -s [repo location]/PHP/JHU [code sniffer location]/src/Standards/JHU
```

Run the following command to get the location of the standards directory:
```bash
pear list-files PHP_CodeSniffer | grep "PHP/CodeSniffer/src/Standards"
```
