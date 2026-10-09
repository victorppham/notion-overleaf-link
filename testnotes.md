<details>
<summary>[Modern computational methods in physics part 1: Diagonalization](https://www.youtube.com/watch?v=LtiiBkolFo8)</summary>
	- quantum phase transitions — transition between exotic quantum phases at T=0
	- occurs as some variable is changed
	- minimum energy of state $`E_0`$
	- phases of matter that could be very useful for future tech
	- <span underline="true">**finite temperature phase transitions**</span>: vary temperature, at $`T=T_c`$ we see change in behavior (Ising model)
		- below a certain temperature, material spontaneously magnetizes, which is a phase transition
	---
	- example: full spectrum diagonalization - solve for every eigenvalue and eigenvector at the same time; upto 24 interacting spins
		- for some hamiltonian $`H`$, diagonalize:
		$$
		UHU^\dagger = D
		$$
	- projection method — Lanczos diagonalization (Krylov)
	- Hamiltonians typically have symmetries — useful for block diagonalization (e.g. conservations, lattices)
	- we can reorganize basis matrices
		![before/after diagonalization](https://prod-files-secure.s3.us-west-2.amazonaws.com/dfab35a9-8874-8141-8885-00039b883c89/646eae8f-2dd9-45c1-bfe4-75d7e0bd0f04/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB4665LICQ353%2F20261009%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20261009T091155Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHEaCXVzLXdlc3QtMiJIMEYCIQCFxdm2n1QgVIHPegQcRNEES2Ujkv82puoxY5wf8Ch%2F9gIhAPf6HlWocyAA%2BCr%2BRyLGas32Xkn%2F482BYKGYpkB1Ig4nKv8DCDoQABoMNjM3NDIzMTgzODA1Igw5CDu9f6OHjYMSowEq3AOy3GIGMwiPY73mdawMZGJ9yNjMOdjX6fDRK5p0f7DAzvw2rb5om5tIhlKoVXpHH26ZVotrarSOHeAWxfdcYL1FuCAhJiI8gSptuTIICTxmBLvT6FmUET4KGBOS6%2FtkobizHLUG5iK3kJn4%2FKqFiFmTrtPO4zASz6yOtcntLOVCf6HTfR2l%2Bj3iNlYfm1XT3UFoPezzfAIhVC%2Bu9qXxXynxFR7vF0nb%2BBiNFl1oVziJF6zSsv5qw4g2MA22V70Prmq46nQQwcZFF2IaF21Yofi70jEK71W3uv8o8HMPosGrLUTmh5Hm1T3phANfoMN%2FOMMjZEKOh2egs669dGoaUnQEsulTxP9JNemxKVv3hGdbTv2HvzEoG9y1bqF4QaYr1DSUfp6%2BeYqTuyPWbBTgi8DsEjIhUmCBiuINlEP%2Fsd7EtCtAK39qAaQj1v7Ff8qpeqqFfHwXzU47gfMMwAkdHW%2Fzk0odsqmOkQXxEgJcljyHQYyQymAS7Cnu7N23McfUyc9xMcoDEHAIHYw%2FXeykAL5Nen%2Bd907D12SvL%2Fj4Xpi0hpjWO28VXqmX4C6sQFcXriUnwMBt3%2FUQFXuOO%2Fd3acR33sniRklB1n3R4p%2FrAV6dbvPCzF5%2FW8xQNxCAMzDMy6LWBjqkAbbMeL61VUavA76jRLpRbDkNjP%2BbvO6gNNgM96Glgq0DINMW%2FM9lFGy7hiCZCdrqNJUZ5nGweWZ%2F4Dm7QmUImk4FqRCCnQaWzQWGowDv%2Fc7FrSKjzxc9MFBkh3Vl6JSOUCGXOWkL5Vywl%2FTWhHo96iX4wsaaxzR0gIiJLx1UmVnFSnZ4zrd%2BobVFoVMO8GlPCMoMTz%2FAPgFmqzYgDtg0OdIIuGcI&X-Amz-Signature=b43c5755e3948ac7ddc789c4a20e218eda4ba8248e11470da32b3587e036b562&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject#notion_record=block.3e5b35a9-8874-805b-9034-d5c02418f630.dfab35a9-8874-8141-8885-00039b883c89)
</details>
<empty-block/>