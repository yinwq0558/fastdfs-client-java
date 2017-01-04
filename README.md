# fastdfs-client-java
FastDFS java client SDK, support ClientGlobal.init(InputStream confIs)

// 2016-12-29 modify
InitFileReader.java add function, load config file from inputstream.
/**
 * @param is config file input stream
 */
	public IniFileReader(InputStream is) throws IOException{
		this.conf_filename = "";
		loadFromStream(is);
	}
