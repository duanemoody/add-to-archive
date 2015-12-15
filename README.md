# Add to Archive
AppleScript droplet for adding files to an archive. 

Select multiple files/folders including one (and only one) archive file, drop them on AtA, and AtA will move the files inside the archive, preserving its original creation date and download metadata.

Because it's based off the 7-Zip compression engine, AtA natively supports every archive format 7-Zip does, except RAR of course. If AtA cannot find 7-Zip support on your Mac, it will prompt you to download Keka (and If AtA detects Brew, adds another button to one-click install the P7Zip library as an alternative).

Due to a security measure in how the Finder silently splits up dropped files to droplets into separate groups if any of them are downloaded from the Internet, AtA will detect files with this bit and clear it before prompting you to drop the files on it a second time.

