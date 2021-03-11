{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "READ ME"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "How to use it: Apache is an open-source and free web server software that powers around 40% of websites around the world. The official name is Apache HTTP Server, and it’s maintained and developed by the Apache Software Foundation. It allows website owners to serve content the name web server. It’s one of the oldest and most reliable web servers, with the first version released more than 20 years ago, in 1995."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "How to Install it: \n",
    "\n",
    "1-Apache listens for requests on TCP/IP port 80. You need to uninstall or disable any program that uses that port. If you have a Professional or Server version of Windows, you may already have IIS installed. If you would prefer Apache, either remove IIS as a Windows component or disable its services.\n",
    "\n",
    "2-We’re going to use the unofficial Windows binary from Apache Lounge. This version has performance and stability improvements over the official Apache distribution, although I’m yet to notice a significant difference. However, it’s provided as a manually installable ZIP file from www.apachelounge.com/download/.\n",
    "\n",
    "3-We’ll install Apache in C:/Apache24, so extract the ZIP file to the root of the C:/ drive. Apache can be installed anywhere on your system, but you’ll need to change SVROOT configuration to point to your unzipped location — suh as E:/Apache24.\n",
    "\n",
    "4-Apache is configured with the text file conf/httpd.conf contained in the Apache folder. Open it with your favorite text editor. Note that all file path settings use a forward slash (/) rather than the Windows backslash. If you installed Apache anywhere other than C:/Apache24, now is a good time to search and replace all references to C:/Apache24.\n",
    "\n",
    "\n",
    "5-Your Apache configuration can now be tested. Open a command box (Start > Run > cmd) and enter:\n",
    "\n",
    "\n",
    "6-The easiest way to start Apache is to add it as a Windows service. Open a new command prompt as administrator, and enter the following:\n",
    "\n",
    "cd /Apache24/bin\n",
    "httpd -k install\n",
    "\n",
    "\n",
    "7-Create a file named index.html in Apache’s web page root (either htdocs or D:\\WebPages) and add a little HTML code:\n",
    "<html>\n",
    "    <head>\n",
    "        <title>Testing Apache</title>\n",
    "    </head>\n",
    "    <body>\n",
    "        <p>Apache is working!</p>\n",
    "    </body>\n",
    "</html>"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "How to Contribute: The Apache Software Foundation uses various licenses to distribute software and documentation, to accept regular contributions from individuals and corporations, and to accept larger grants of existing software products.\n",
    "\n",
    "These licenses help us achieve our goal of providing reliable and long-lived software products through collaborative open source software development. In all cases, contributors retain full rights to use their original contributions for any other purpose outside of Apache while providing the ASF and its projects the right to distribute and build upon their work within Apache."
   ]
   
   Why I used Apache was because it seemed very interesting. It is also a program I have heard my dad use so I decided to use it.
  
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
