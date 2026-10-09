**[Modern computational methods in physics part 1: Diagonalization](https://www.youtube.com/watch?v=LtiiBkolFo8)**

- quantum phase transitions — transition between exotic quantum phases at T=0
- occurs as some variable is changed
- minimum energy of state $E_0$
- phases of matter that could be very useful for future tech
- **finite temperature phase transitions**: vary temperature, at $T=T_c$ we see change in behavior (Ising model)
    - below a certain temperature, material spontaneously magnetizes, which is a phase transition
---
- example: full spectrum diagonalization - solve for every eigenvalue and eigenvector at the same time; upto 24 interacting spins
    - for some hamiltonian $H$, diagonalize:
    $$
    UHU^\dagger = D
    $$
- projection method — Lanczos diagonalization (Krylov)
- Hamiltonians typically have symmetries — useful for block diagonalization (e.g. conservations, lattices)
- we can reorganize basis matrices
    ![before/after diagonalization](https://prod-files-secure.s3.us-west-2.amazonaws.com/dfab35a9-8874-8141-8885-00039b883c89/646eae8f-2dd9-45c1-bfe4-75d7e0bd0f04/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAZI2LB466XUPPB3II%2F20261009%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20261009T093914Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHEaCXVzLXdlc3QtMiJIMEYCIQC5fJWlX01wlsVPtHZ6t7ObwpUSG3316%2F5Pt3UutLmiigIhANCgL7LLVqQoS9fMdMuX1Urg8LfvrX%2Fo28e31LTi49C1Kv8DCDkQABoMNjM3NDIzMTgzODA1Igy%2BFHJZ%2B1qXL1%2Fa0KEq3AN%2B2nlgVERoTzfEavGEkJP%2F%2BpzIvyDBBgUmDqAKuu0uBo6cWcbISLGqb7PrFmMS4WZSjjUaeNJMXJEGFhWzJh2soXEiKAWU%2BuRHWB7%2FgvxeKaK6CLh152HBjzHVtq1%2BL7K5BvS63uaA6dv7dV0hO5Q3gfYy%2FPBofEq%2Fh1kmKzkSMCKNzJzqI52w1KIYXEzTuO9z776y%2FT6J%2FbIXyOX6iK93PC0Tw0axJuDY3PoFLrMKAaTJAb3V8Kcvx26KNqlhiIz9nJvlZ3IySZfNHO7M%2BLyvB4ucgbKAcyXa3WhGugobiXocKG8gV5CkLJ9c6En02TiQIz2Ger6PmyLRpn8%2Bul5kJYkBzoVmqc5gEGscj8l8JNtpDh63bGii6d0QDvn8xcM97KK4Gjr7CNOBEWLu0ZxzIaJPgTR9V13otUG2njHWNSkmCb6JYvaN0JwwcJGyS5GLTPGO3X4iYmFadCFHR50VTZQte574XuOnKFib9Ne4V1%2F%2B%2FJbLwfclmOi79LxBaAN3t%2BKR9o78uWSk2gztJiwqwfKxSeyE1mWY%2FsWXiyStWj2zUkO5ytzibFCOc5Gj5Abz9gLRPOlt6v1ZLck9dkfrdM6%2F6IjFlxqq7Ah3cuKNnNwrWSGnXVDcYMQoTjD7yqLWBjqkAYzxT8XpF1GVvSZV4gyaLog0%2FIGgagqd4T%2BqhP9pU62Yfa2T%2BySNW42JGR7bX%2F9wSlfh8NhlfqrqOJva%2Bn%2BQPi%2BYUpblsp%2F9d8Wp0Ros6Q0AIYmWFLrHYawW0gcBZkS0PRYJZgQ%2FEWVlR7tGX%2FAc01eAlbBjhBvdH7g92yUEDrOzKNy1sm3wRAQ13cXgD4TLt%2B3y4372fAdUOp6zbjfawuOtIJM8&X-Amz-Signature=d3f4275067b86762be7541ad23109443566a98c76b9f06e07f07ae8fe30415e9&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject#notion_record=block.3e5b35a9-8874-805b-9034-d5c02418f630.dfab35a9-8874-8141-8885-00039b883c89)
