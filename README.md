Very simple HTTP API page using GREEN API that integrates with WhatsApp.

1. Get idInstance and apiTokenInstance from GREEN-API developer account.

2. Use getSettings to get instance info and getStateInstance to get its current state (authorized = running and ready to work).

3. Use sendMessage to send a regular text message to a specified phone number.

4. Use sendByFileUrl to send a file of most common types to a specified phone number. As this API call supports both direct file URLs and links to external storages (Google Drive, Dropbox or similar) that rely on internal indexing, a fileName containing correct extention must be specified along with file URL.
