# Tech

## HDdata 

HDdata is a decentralized key-value store that allows users to store content using HDName-derived keys. HDName is a human-readable namespace that enables Web3 URLs to point to validated content on a decentralized backend. By using HDName-derived keys, HDdata makes it much easier to reference and access decentralized content.

IPFS is the default storage backend for HDdata, ensuring that content is stored in a distributed and censorship-resistant manner. This means that the content can be accessed from anywhere in the world, and it cannot be taken down by any single entity.

HDdata also employs a commit system, where users sign with their keys and make a commit to send content to publishers. This ensures that content is secure and tamper-proof, as each commit is cryptographically signed by the user. The commit system also allows for a more efficient and streamlined process for content creation and publishing.

Cortex Network and HDdata Cortex Network is a decentralized platform for content creation and distribution. HDdata is a key component of Cortex Network, enabling users to store and access decentralized content efficiently.

Using HDdata, users can easily store content using their HDName-derived keys. They can also make commits to send content to publishers securely. Anyone with a .crtx domain and a staked amount of $CRTX can become a publisher, allowing for a more decentralized and democratic content creation process.

HDdata also integrates seamlessly with Cortex Network's HDindex, which is a modified sparse Merkle trie that defines the local state and allows for fast content lookups. This ensures a high level of efficiency and low-cost state management, generating globally verifiable localized consensus.

Conclusion HDdata is a powerful tool for decentralized content creation, allowing users to store and access content in a distributed and censorship-resistant manner. Its use in Cortex Network enables a more efficient and streamlined content creation process, with a focus on decentralization and security. 

## HD Index

HDindex is a modified sparse Merkle trie that allows for fast content lookups and defines the local state in the Cortex Network. This high-efficiency, low-cost state management system generates globally verifiable localized consensus, making it a valuable tool for content publishing on the Cortex Network.
How HDindex Works

HDindex uses a modified sparse Merkle trie to store the local state of the Cortex Network. Each node in the trie represents a unique key, which is derived from the HDName system. HDName is a hierarchical deterministic naming system that allows for the creation of unique and human-readable names.

When users publish content on the Cortex Network, their data is stored in IPFS, a decentralized file storage system. The user then creates a commit, which is a signed message that contains the key and the IPFS hash of the content. The commit is then sent to the publisher, who verifies the signature and stakes CRTX to publish the new state on-chain.

Once the new state is published on-chain, it is added to the HDindex trie. The trie provides a way to quickly and efficiently look up the content by its key, which is derived from the HDName system. This enables fast content discovery and retrieval on the Cortex Network.

### Benefits of HDindex

HDindex provides several benefits to content creators and publishers on the Cortex Network. Firstly, it allows for fast and efficient content discovery and retrieval, making it easy for users to find the content they are looking for. Secondly, the use of the Ethereum blockchain and the HDName system ensures that the content is stored securely and can be easily verified by anyone.

Additionally, HDindex is a low-cost state management system that generates globally verifiable localized consensus. This means that the state of the Cortex Network can be This means that the state of the Cortex Network can be easily verified by anyone, making it a transparent and trustworthy platform for content publishing.

### Conclusion
HDindex is a key component of the Cortex Network that allows for fast and efficient content discovery and retrieval. Using the HDName system, HDindex provides a secure and transparent platform for content creation and distribution. Its low-cost state management system generates globally verifiable localized consensus, making it a valuable tool for content publishing on the Cortex Network.

## HDname

HDName is a namespace system used in Cortex Network for decentralized content creation. It allows for human-readable names to be associated with keys, which can be used as Web3 URLs to point at validated content on a decentralized backend, similar to a URL in web2, but now every URL has an associated key-pair. The use of HDName makes it much easier to reference information on the Cortex Network, as the names are more memorable and easier to type than the long hexadecimal strings typically used in decentralized systems.

The HDName system is built on top of the Ethereum Name Service (ENS) and uses its smart contract infrastructure to manage name registrations and resolution. When a user registers a name on the Cortex Network, they are essentially creating a mapping between the name and a unique key that can be used to retrieve the associated content. This mapping is stored on the ENS smart contract, which is replicated across the network to ensure availability and redundancy.

To resolve a name to its associated content, a user simply needs to query the ENS smart contract with the name and receive the corresponding key in return. The key can then be used to retrieve the content from the decentralized backend, which is typically stored on IPFS. The content can be anything from text and images to video and audio, and can be validated using various mechanisms to ensure its authenticity and integrity.

The use of HDName on Cortex Network is particularly useful for content creators and publishers, as it allows them to easily share their content with others using a memorable and easily accessible name. This can help to increase the visibility and reach of their content, and make it more discoverable by users who may not be familiar with the underlying technical infrastructure.

Overall, HDName is a powerful tool for decentralized content creation on the Cortex Network. By providing a human-readable namespace for keys, it makes it much easier to reference and share content, and helps to promote the adoption of decentralized systems by making them more accessible to the average user.

