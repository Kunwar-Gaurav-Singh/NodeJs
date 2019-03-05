Node is a wrapper around VM like V8 with built in module providing rich features with easy to use sync API's.
It has reliable package manager(NPM) and module dependency manager(CommonJs) which makes it a lot easier for developers.
Non blocking async nature is also one of the most powerful point.(Works with a single thread).

Modules example-
http.createServer(req, res) only creates a server but doesn't make it available for use.
we have to use server.listen(portNumber, callback) to activate the created server. Listen also keeps the node process busy and doesn't exit. Which is not the case with other processes.