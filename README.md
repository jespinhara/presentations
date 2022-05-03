# Talks

- Adventure Time Cont - Warsaw (Anti-Fraud) Software
  ```Around the world frauds represent the biggest threats to financial institutions, 
  especially banks, many of which are investing significant amounts of money
  in modern anti-fraud systems that do not completely prevent abuses, but
  actually reduce the losses.

  Brazil is not different in this regard, with frauds becoming a real nightmare
  to the banks. As is widely known, Brazil has a huge active cyber crime scene,
  mainly focused in banking frauds through banking malware. Brazilian banks found
  a very creative solution, or as in the famous Brazilian slang, 'jeitinho
  brasileiro[1]' to try to stop/reduce the frauds performed through Internet
  Banking systems. Their solution was to transfer the security checks to the
  client side.

  Warsaw is a software developed by Gas Tecnologia, part of Diebold group, and
  has become the industry security standard solution used by most Brazilian
  banks. Under the guise of protecting the customer's online banking
  transactions, Warsaw is mandatory to be installed on personal computers which
  use need access to Internet Banking, with no alternatives left to bank
  customers.

  What is the problem with a security solution such as Warsaw, though? In short,
  it works very similarly to a rootkit. While this behavior can be more clearly
  observer in the Windows version of the software, similar invasive techniques
  are also used in the OSX version. I have started to reverse engineer the
  software trying to gather evidence to confirm Warsaw's disregard for the
  user's privacy, and ended up finding that the software does not follow security
  best practices, and might actually expose user information which can be used to
  deliver tailored bank malware.
  ```
  - https://github.com/jespinhara/presentations/blob/main/YSTS%20-%20Adventure%20Time%20Cont%20-%20Ruxmon%20v0.pdf
