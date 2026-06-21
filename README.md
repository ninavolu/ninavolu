# Neel Inavolu

Rising senior at Fulton Science Academy in Atlanta. I build software end to end and put it in front of real users. Most of what I make starts with messy real-world data and ends with something a person or a business can actually use.

### What I've built

**Order-tracking inventory SaaS.** An email-to-inventory pipeline that reads order emails across up to 8 Gmail inboxes, sends each one to the Claude API for structured field extraction, deduplicates by order number, and logs everything to a live dashboard. I sold it as a $50/month subscription to a six-figure reselling brand and ran the whole thing myself, from OAuth setup to customer delivery.

**pixlib: Image Library MCP server.** A Model Context Protocol server that lets Claude search and manage an image library inside a normal conversation. I took it from a local prototype to a hosted, multi-tenant product: Clerk OAuth, Supabase (PostgreSQL plus storage) with indexed tag search, served over Streamable HTTP on Railway. Live at [pixlib.app](https://pixlib.app).

**HIPAA-aware zero-knowledge proof system.** Proves a patient qualifies for a clinical trial without revealing their medical record. I wrote a Circom circuit compiled to R1CS, proved it with Groth16 zk-SNARKs over the BN254 curve, and bound each proof to one record with a two-stage Poseidon hash. Two separate services model a hospital and a trial sponsor that don't trust each other; the sponsor only ever learns eligible: true or false. Live at [hipaa-zkp.netlify.app](https://hipaa-zkp.netlify.app).

### Robotics

I've competed in VEX robotics since 2018. My team reached the World Championship Division Finals out of 834 teams in 2025 and won the Think Award, the top programming award, at the Georgia state championship. I write the C++ for PID and odometry motion control. I also coach three high school teams and wrote a 14-week C++ curriculum that has taken middle and high schoolers from block code to real-time control.

### Tools I work with

C++, Python, Java, JavaScript / Node, Dart / Flutter, SQL. REST APIs, OAuth 2.0, Express. Supabase / PostgreSQL, Cloudflare R2, Railway, Netlify. Anthropic Claude API and the Model Context Protocol. Circom and snarkjs for zero-knowledge proofs.

### Reach me

- Projects: [pixlib.app](https://pixlib.app), [hipaa-zkp.netlify.app](https://hipaa-zkp.netlify.app)
- LinkedIn: [neel-inavolu](https://www.linkedin.com/in/neel-inavolu-6996a936a/)
- Email: ninavolu7@gmail.com
