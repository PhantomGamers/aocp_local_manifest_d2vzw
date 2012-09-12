Local manifest addon for AOCP (jb)
Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Make a build directory:

	mkdir Andoid (or whatever name you choose)
	cd Android (or the name  you chose)
	

To initialize your local repository using the AOKP manifest, use commands like these:

    repo init -u https://github.com/xAOCPx/platform_manifest.git -b jellybean
    
    curl -L -o .repo/local_manifest.xml -O -L https://raw.github.com/PhantomGamers/aocp_local_manifest_d2vzw/jb/local_manifest.xml

    	( or Download: https://github.com/PhantomGamers/aocp_local_manifest_d2vzw/blob/jb/local_manifest.xml
		and place it in ~/Android/.repo/local_manifest.xml (or ~/'name you chose'/.repo)

Then to sync up:

    repo sync
