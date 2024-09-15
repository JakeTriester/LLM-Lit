Name: Jake Triester
LLM: ChatGPT-4o mini
Question: How has the evolution of programming languages, from assembly languages (like MIPS), to high-level languages (like python), affected both software and hardware development?

## Concepts

## References
- [Ceruzzi, A History of Modern Computing](https://books.google.com/books?hl=en&lr=&id=x1YESXanrgQC&oi=fnd&pg=PR5&dq=A+history+of+modern+computing&ots=ZL_Bpa3mX2&sig=dRs_74gJ-Qw5XPdx1FacKAw3OE8#v=onepage&q=A%20history%20of%20modern%20computing&f=false)
- [Hennessy & Patterson, Computer Architecture: A Quantitative Approach](https://books.google.com/books?hl=en&lr=&id=cM8mDwAAQBAJ&oi=fnd&pg=PP1&dq=Computer+Architecture:+A+Quantitative+Approach%22+by+John+L.+Hennessy+and+David+A.+Patterson+&ots=SJXaGgZUve&sig=2FDeFzLkdKu7p53_j0rd118Qiy4#v=onepage&q=Computer%20Architecture%3A%20A%20Quantitative%20Approach%22%20by%20John%20L.%20Hennessy%20and%20David%20A.%20Patterson&f=false)
- [Dijkstra, Structured Programming](https://dl.acm.org/doi/abs/10.5555/1243380)

## Discussion
### Me:
How has the evolution of programming languages, from assembly languages (like MIPS), to    high-level languages (like python), affected both software and hardware development?

### GPT: 
The evolution from assembly languages to high-level languages has significantly impacted both software and hardware development. High-level languages like Python abstract complex hardware instructions, enabling faster software development and improving programmer productivity. This abstraction has allowed software to become more complex, portable, and scalable. On the hardware side, processors have evolved to support more sophisticated instruction sets and optimizations, such as pipelining and multi-threading, to handle the demands of high-level languages. Furthermore, high-level languages have contributed to the rise of virtual machines and managed runtime environments, influencing modern hardware architectures to prioritize general-purpose computing and energy efficiency.

#### Comment:
At this point I realized that the LLM was solely giving me positive consequences of the evolution, so I decided to ask about the negative ones.

### Me:
Has the increased use of high-level languages caused any negative consequences

### GPT: 
Yes, the increased use of high-level languages has led to some negative consequences. One major drawback is reduced performance, as high-level languages often introduce overhead due to abstraction layers and runtime environments. This can result in less efficient use of system resources compared to low-level languages like assembly. Additionally, the ease of development in high-level languages sometimes encourages less optimized code, leading to larger memory footprints and slower execution. Lastly, high-level languages can distance developers from understanding hardware intricacies, which may lead to less effective debugging and performance tuning in critical applications.

### Me:
Was there a point in history where there was a huge change from the low-level to high level languages

### GPT: 
Yes, a major shift from low-level to high-level languages occurred in the late 1950s and early 1960s with the development of languages like Fortran (1957) and COBOL (1959). These languages introduced much higher levels of abstraction compared to assembly languages, allowing programmers to write more complex software with less focus on hardware details. This period marked a transition towards more human-readable syntax, enabling wider adoption of programming by engineers and scientists. The shift was accelerated by the need for more complex business and scientific applications, and it laid the foundation for modern programming practices.

### Me:
Did this shift lead to a lot more people becoming programmers and/or businesses using more programming?

### GPT: 
Yes, the shift to high-level languages greatly expanded the number of programmers and increased the use of programming in businesses. High-level languages made coding more accessible to people without deep hardware knowledge, allowing more engineers, scientists, and eventually business professionals to write software. Businesses adopted programming for a wider range of applications, including data processing, financial systems, and inventory management. This shift also led to the growth of software development as a profession and the emergence of the commercial software industry, fueling broader adoption of computing across sectors.

## Summary
As I am currently taking CPSC-351 (Computer Architecture) right now, I was interested in the differences between low-level assembly languages, and high-level languages. After chatting with an LLM about the differences and evolution, I learned a lot of new things. One of the more interesting things that I learned was a couple of negative consequences from the evolution from low-level to high-level languages. The LLM brought up a very interesting point that while high-level code is very beneficial for a multitude of reasons, it has led to less understanding on the human side. Since, as humans, we don't need to fully understand how the hardware works to write high-level code, we generally don't. This won't cause huge problems, but it can lead to less optimized code that uses up more memory than it needs to. I had another interesting discovery when I asked about the history of the shift from low-level to high-level code in industry. I learned this shift took place during the late 50s and early 60s, which is way earlier than I was expecting. Since computer programming is a relatively new field, I was more expecting towards the end of the 70s when that shift was made. Overall, the LLM was very effective in teaching me about the evolution of programming languages and what effect it had on the industry.
