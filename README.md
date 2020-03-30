# List Command Rita <small>$version</small>

<table class="table">

<thead>

<tr>

<th>Nama</th>

<th>URL</th>

<th>Keterangan</th>

</tr>

</thead>

<tbody>

<tr>

<td colspan="3">**Login**</td>

</tr>

<tr>

<td>OTP</td>

<td>http://$url/otp?msisdn=$msisdn&id_retailer=xxx</td>

<td> </td>

</tr>

<tr>

<td>Verify OTP</td>

<td>http://$url/verifyOtp?msisdn=$msisdn&otp=xxx</td>

<td> </td>

</tr>

<tr>

<td colspan="3">**INFO**</td>

</tr>

<tr>

<td>Balance</td>

<td>http://$url/balance?msisdn=$msisdn</td>

<td> </td>

</tr>

<tr>

<td>History</td>

<td>http://$url/history?msisdn=$msisdn</td>

<td>opsional &limit=1, opsional &date=20190818</td>

</tr>

<tr>

<td colspan="3">**KPK**</td>

</tr>

<tr>

<td>Produk KPK</td>

<td>http://$url/product_kpk?msisdn=$msisdn</td>

<td> </td>

</tr>

<tr>

<td>TRX KPK</td>

<td>http://$url/kpk?msisdn=$msisdn&pin=xxx&to=xxxxxxxx&code=xxx&price=xxx</td>

<td> </td>

</tr>

<tr>

<td>Check KPK</td>

<td>http://$url/check_kpk?msisdn=$msisdn&to=xxxxxxx</td>

<td> </td>

</tr>

<tr>

<td colspan="3">**SPV**</td>

</tr>

<tr>

<td>Produk SPV Blank</td>

<td>http://$url/product_spv_blank?msisdn=$msisdn</td>

<td> </td>

</tr>

<tr>

<td>TRX SPV Blank</td>

<td>http://$url/spv_blank?msisdn=$msisdn&pin=xxx&to=xxxxxxxx&code=xxx&price=xxx</td>

<td> </td>

</tr>

<tr>

<td>Produk SPV 0</td>

<td>http://$url/product_spv0?msisdn=$msisdn</td>

<td> </td>

</tr>

<tr>

<td>TRX SPV Blank</td>

<td>http://$url/spv0?msisdn=$msisdn&pin=xxx&to=xxxxxxxx&voucher=xxx&price=xxx</td>

<td> </td>

</tr>

<tr>

<td>Check SPV By Nomor Induk Voucher</td>

<td>http://$url/check_spv_induk?msisdn=$msisdn&no=xxxxxxx</td>

<td> </td>

</tr>

<tr>

<td>Check SPV By Nomor Seri Voucher</td>

<td>http://$url/check_spv_seri?msisdn=$msisdn&no=xxxxxxx</td>

<td> </td>

</tr>

<tr>

<td colspan="3">**ISI ULANG**</td>

</tr>

<tr>

<td>Produk ISI ULANG</td>

<td>http://$url/product?msisdn=$msisdn</td>

<td> </td>

</tr>

<tr>

<td>TRX PULSA</td>

<td>http://$url/pulsa?msisdn=$msisdn&pin=xxx&to=xxxxxxxx&code=xxx&price=xxx</td>

<td> </td>

</tr>

<tr>

<td>TRX PAKET DATA</td>

<td>http://$url/paket?msisdn=$msisdn&pin=xxx&to=xxxxxxxx&code=xxx&price=xxx</td>

<td> </td>

</tr>

</tbody>

</table>
