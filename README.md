# Final-Project

Project Submission for the Encode zkML Bootcamp

Purpose of Project:

GainForest.Earth is a decentralized science non-profit and XPRIZE Rainforest winner.
GainForest pays for environmental data, such as photographs or wildlife audio, collected by indigenous communities to help organizations build more sustainable products. Using the gathered data, publicly available ML models like BioCLIP, or BirdNET, can be applied to determine the ecological diversity of the region. This enables more accurate visualisations of nature.

However, one current issue is the reluctance by local communities to share sensitive data, since this can invite poachers or other ecological abuses. Zero-knowledge proofs offer a way around this problem. By using the image as a witness to a zkML-circuit, a proof can be shared that the user at least possesses a photo that satisfies certain biodiversity criteria, without them ever having to disclose it. In order to assure the image is legitimate, some kind of attested input would need to be used. We have already seen similar hardware with the ZK-Microphone.

Short Summary:

The feasibility of the approach is illustrated with a simple POC. We build a CNN against images supplied by GainForest that classifies the taxonomic order of a plant. Then, we export it to the ONNX format and use the EZKL library make a prediction and produce a proof.
