# Idemcore

**Bit-exact LLM inference.** The same input yields identical tokens and identical hashes on every run, across supported hardware.

Every generated or scored token comes with a verifiable per-token receipt: a hash log that anyone can recompute and compare, without having to trust us.

- 🌐 Website: <https://idemcore.net>
- 📄 Paper: <https://doi.org/10.5281/zenodo.23851129>
- ✅ Verifier (open source, dependency-free Python): <https://github.com/idemcore/idemcore-verifier>
- ✉️ Contact: [don.wick@idemcore.net](mailto:don.wick@idemcore.net)

To check the published measurements yourself:

```sh
git clone https://github.com/idemcore/idemcore-verifier
cd idemcore-verifier && pip install . && idemcore-verify samples
```
