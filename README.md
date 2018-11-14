# yis

Yiff on IPFS System

A system to collect data from e621, analyse the contents for similarity, then publish the results on ipfs/ipld.

Consists of four components.

- Database: stores non-file contents.
- Retrieval: pulls posts, tags, and favs from e621.
- Analysis: evaluates similarities
- Distribution: Compresses and serve content via https/ipfs

- [ ] Preliminary database functionality
- [ ] Complete database functionality

- [ ] Preliminary retrieval functionality
- [ ] Complete retrieval functionality
- [ ] Cooperative retrieval functionality
- [ ] furaffinity support

- [ ] Symmetric similarity generation and storage

- [ ] web interface for browsing database and similarities
- [ ] framework for ipfs distribution
- [ ] ipfs distribution

- [ ] publish



### Restrictions

- limited to posts > 5 score and > 20 favcount
- images are stored compressed, and not to exceed 20 Mpix
