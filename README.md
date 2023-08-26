# Stupid-errors-that-took-me-more-than-1-hour-to-solve

## snap install

**ERROR**: tls: failed to verify certificate: x509: certificate signed by unknown authority  
**Solution**: https://kb.acronis.com/content/68323  
**Explanation**: certificates might be impaired.

## apt-get/apt install

**ERROR**: Temporary failure resolving 'cn.archive.ubuntu.com'  
**Solution**: [https://kb.acronis.com/content/68323](https://askubuntu.com/questions/257290/configure-proxy-for-apt)https://askubuntu.com/questions/257290/configure-proxy-for-apt  
**Explanation**: apt-get/apt does not recognize the proxy from the environment and we need to configure it separately.
