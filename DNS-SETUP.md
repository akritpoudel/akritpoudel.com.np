# DNS Configuration for akritpoudel.com.np

## ✅ GitHub Configuration Complete

The CNAME file has been added to your repository. GitHub is now expecting the domain `akritpoudel.com.np`.

---

## 🌐 DNS Configuration Required

To make your website accessible at **http://akritpoudel.com.np**, you need to configure DNS records with your domain registrar.

### Step 1: Register the Domain

If you haven't already, register the domain **akritpoudel.com.np** with a registrar that supports .com.np domains:

**Recommended Registrars for .np domains:**
- Mercantile Communications (official .np registrar)
- Web.com.np
- HostingNepal
- Websitebuilder.com.np

### Step 2: Configure DNS Records

Once you have the domain, log into your domain registrar's DNS management panel and add these records:

#### Option A: Using CNAME (Recommended)

```
Type: CNAME
Name: www
Value: akritpoudel.github.io
TTL: 3600 (or default)
```

```
Type: A
Name: @
Value: 185.199.108.153
TTL: 3600

Type: A
Name: @
Value: 185.199.109.153
TTL: 3600

Type: A
Name: @
Value: 185.199.110.153
TTL: 3600

Type: A
Name: @
Value: 185.199.111.153
TTL: 3600
```

#### Option B: Using A Records Only (Alternative)

```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153

Type: CNAME
Name: www
Value: akritpoudel.github.io
```

### Step 3: Wait for DNS Propagation

- DNS changes can take 1-48 hours to propagate globally
- Usually takes 1-4 hours for most regions
- Check propagation status at: https://www.whatsmydns.net/#A/akritpoudel.com.np

### Step 4: Verify Domain in GitHub

After DNS is configured:

1. Go to: https://github.com/alishaha29/akritpoudel.com.np/settings/pages
2. The custom domain should show as **verified** ✅
3. Check "Enforce HTTPS" (recommended)

---

## 🔍 Checking DNS Configuration

### Method 1: Command Line

```bash
# Check A records
dig akritpoudel.com.np +short

# Expected output:
# 185.199.108.153
# 185.199.109.153
# 185.199.110.153
# 185.199.111.153

# Check CNAME for www
dig www.akritpoudel.com.np +short

# Expected output:
# akritpoudel.github.io
```

### Method 2: Online Tools

- https://www.whatsmydns.net/#A/akritpoudel.com.np
- https://mxtoolbox.com/SuperTool.aspx?action=a%3aakritpoudel.com.np

---

## 📋 DNS Configuration Checklist

- [ ] Domain akritpoudel.com.np registered
- [ ] A records added (4 records pointing to GitHub IPs)
- [ ] CNAME record added (www → akritpoudel.github.io)
- [ ] Wait 1-48 hours for DNS propagation
- [ ] Verify at https://www.whatsmydns.net
- [ ] Check GitHub Pages settings show "DNS check successful"
- [ ] Enable "Enforce HTTPS" in GitHub Pages settings

---

## 🌟 Current Status

- ✅ CNAME file created and pushed to GitHub
- ✅ GitHub is configured to expect akritpoudel.com.np
- ⏳ Waiting for DNS configuration
- ⏳ Waiting for DNS propagation

---

## 🔗 URLs

### Current Working URLs:
- **GitHub Pages**: https://akritpoudel.github.io/akritpoudel.com.np/ ✅ (Working Now)

### Future Custom Domain URLs (after DNS setup):
- **Custom Domain**: http://akritpoudel.com.np ⏳ (Requires DNS)
- **Custom Domain with WWW**: http://www.akritpoudel.com.np ⏳ (Requires DNS)
- **HTTPS Custom Domain**: https://akritpoudel.com.np ⏳ (After DNS + GitHub verification)

---

## ⚠️ Important Notes

1. **Domain Registration**: You must register the domain first before DNS will work
2. **DNS Propagation**: Changes take time - be patient
3. **HTTPS**: Will be available automatically after DNS is verified by GitHub
4. **Backup URL**: The GitHub Pages URL will always work as a backup

---

## 🆘 Troubleshooting

### Issue: Domain not resolving
**Solution**:
- Wait longer (DNS can take up to 48 hours)
- Check DNS records are correct
- Try flushing DNS cache: `sudo dscacheutil -flushcache`

### Issue: "DNS check unsuccessful" in GitHub
**Solution**:
- Verify all 4 A records are added correctly
- Check CNAME file exists in repository
- Wait for DNS propagation
- Try removing and re-adding custom domain in GitHub settings

### Issue: Site shows 404
**Solution**:
- Ensure CNAME file contains: `akritpoudel.com.np`
- Check GitHub Pages is enabled
- Verify DNS records point to correct IPs

---

## 📞 Need Help?

- **GitHub Pages Documentation**: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
- **DNS Propagation Checker**: https://www.whatsmydns.net
- **GitHub Pages Status**: https://github.com/akritpoudel/akritpoudel.com.np/settings/pages

---

**Summary**: The CNAME file is configured on GitHub. Now you need to register the domain `akritpoudel.com.np` and configure DNS records with your registrar.
