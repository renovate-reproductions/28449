# Expected
PR should try to update to `node:20.12.2-bullseye@sha256:127328164f9b593a2f23725a0525bafce697a6edce92fbf51a255dc6ae70af86` (correct bullseye image [link](https://hub.docker.com/layers/library/node/20.12.2-bullseye/images/sha256-sha256:127328164f9b593a2f23725a0525bafce697a6edce92fbf51a255dc6ae70af86?context=explore))

# Current behavior
PR tries to update to `node:20.12.2-bullseye@sha256:844b41cf784f66d7920fd673f7af54ca7b81e289985edc6cd864e7d05e0d133c` (which is the non bullseye image, [link](https://hub.docker.com/layers/library/node/20.12.2/images/sha256-844b41cf784f66d7920fd673f7af54ca7b81e289985edc6cd864e7d05e0d133c?context=explore))


# Discussion link
https://github.com/renovatebot/renovate/discussions/28449