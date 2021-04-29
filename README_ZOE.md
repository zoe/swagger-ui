This is a fork of swagger_ui to support retrieving an `id_token` from google sign in.
We are adding exactly 3 letters to the repository (but doing it well is a bit more involved)

To update:
1. pull the latest version of swagger from the origin
2. merge into the branch `id_token`
3. build a dist file `npm run build-dist`
4. copy the file here: `https://storage.googleapis.com/zoe-net-static-assets/swagger-ui-bundle.js`