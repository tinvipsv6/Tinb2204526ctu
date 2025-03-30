
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <title>Quản lý đào tạo - TRƯỜNG ĐẠI HỌC CẦN THƠ</title>
        <meta name="robots" content="index, follow" />
        <meta name="keywords" content="" />
        <meta name="description" content="CUSC" />
        <meta name="generator" content="CUSC - Can Tho University Softwave Center" />
        <meta http-equiv="cache-control" content="public" />
        <link rel="stylesheet" type="text/css" href="templates/css/template.css"/>
		<script language="javascript" src="includes/jquery-1.6.js"></script>
		<style>
			.thong_bao_temp{
				padding:10px;
				margin-top:5px;
				color:blue;
				borde:1px solid #ddd;
				line-height:24px;
				font-size:15px;
				text-align:left;
			}
			.thong_bao_temp>div{
				text-align:left;
				padding:5px;
			}
			.thong_bao_temp>a{
				padding:5px;
			}
			.thong_bao_temp>a:hover{
				color:red
			}
                        #newthongbao {
                        animation: color-change 2s infinite;
                        }

                        @keyframes color-change {
                        0% { color: red; }
                        25% { color: blue; }
                        50% { color: orange; }
                        75% { color: green; }
                        100% { color: red; }
                        }
		</style>
    </head>
    <body>
    <div id="page-container">
       <div id="page-header">
                   <div id="header">
            <div id="banner">
                <div id="div-control">
                                    </div>
                    <a id="btn-homepage" href="" title="Trang chủ">Trang chủ</a>
            </div>
        </div>
<script>	
    function thoat(url) {
        if (confirm('Ban co chac chan muon thoat khong ?' )) {
            document.location = url+'/logout.php';
            return;
        }
    }
</script>		          </div>
       <div id="page-body"> 
           <table id="table-main" width="980" align="center" border="0" cellpadding="0" cellspacing="0">
            <tr>
                <td width="400" align="center" valign="top">
                    <form method="post" action="detect.php" name="frmLogin" autocomplete="off">
                        <table id="login-sv" class="login" width="100%" align="center" border="0" cellpadding="0" cellspacing="0">
                            <tr>
                                <td class="bg-module-top"></td>
                            </tr>
                            <tr>
                                <td class="bg-module-middle" align="center">
                                    <input type="text" id="txtDinhDanh" class="username" name="txtDinhDanh" value="" placeholder="Mã số đăng nhập"/>
                                    <input type="password" id="txtMatKhau" class="password" name="txtMatKhau" value="" placeholder="Mật khẩu" />
                                </td>
                            </tr>
							<tr>
                                <td class="bg-module-middle" align="left" style='padding-left:26px'>
									<input type="text" id="txtMaBaoVe" class="password" name="txtMaBaoVe" value="" placeholder="Mã bảo vệ" style='width:100px; text-align:center'/>
									<img id="verify_code" onclick="document.getElementById('verify_code').src='capcha/securimage_show.php?sid='+Math.random();" title="Đổi mã khác">
                                </td>
                            </tr>
                            <tr>
                                <td class="bg-module-middle" align="center">
                                    <input type="submit" class="btn-login" name="login" value="" />
                                </td>
                            </tr>
                            <tr>
                                <td class="bg-module-bottom">&nbsp;</td>
                            </tr>
                        </table>
                    </form>
                    <div class="thong_bao_temp">
				<!--
					<div>Để truy cập hệ thống tích hợp từ ngoài Trường, sinh viên vui lòng truy cập từ một trong 2 máy chủ sau:</div>
					<a href="https://dkmh5.ctu.edu.vn/htql/login.php">Máy chủ ĐKHP 01</a>&nbsp;
					hoặc 
					&nbsp;<a href="https://dkmh6.ctu.edu.vn/htql/login.php">Máy chủ ĐKHP 02</a> 
				--><font color="#000000">
					Chú ý:
					<br />Mã bảo vệ là nhập các ký tự trên hình <font color="#FF0000">phía bên phải của ô mã bảo vệ</font>.
					
					</font>
					
					<!--Hiện tại hệ thống tích hợp phần dành cho sinh viên (đăng ký học phần, lập kế hoạch học tập...) đang quá tải. Tạm thời Trường <strong>không mở </strong>cho sinh viên truy cập từ ngoài trường. Nếu điều kiện cho phép các em giúp vào Trường để đăng ký học phần hoặc điều chỉnh kế hoạch học tập.
					<span style='color:red'><br/>Dự kiến sẽ mở cho sinh viên truy cập ngoài trường từ 13:30 ngày 16/12/2014.</span>
					-->
					<!--<div>- Hiện tại hệ thống tích hợp phần dành cho sinh viên (đăng ký học phần, lập kế hoạch học tập...) đang quá tải, nên tạm thời Trường chỉ có thể mở cho sinh viên sử dụng từ ngoài trường từ 11g30 đến 13g30 và từ 17g30 đến 7g30 sáng hôm sau.</div>

<div>- Rất mong các em thông cảm, nếu điều kiện cho phép các em giúp vào Trường để đăng ký học phần hoặc điều chỉnh kế hoạch học tập.</div>

<div>- Để vào hệ thống từ 11g30 đến 13g30 và từ 17g30 đến 7g30 sáng hôm sau xin nhấn <a href="https://dkmonhoc.ctu.edu.vn/htql/login.php">vào đây</a>.</div>-->
<!-- <div>- Để vào hệ thống từ 11g30 đến 13g30 và từ 17g30 đến 7g30 sáng hôm sau xin truy truy cập <a href="https://dangkymh.ctu.edu.vn/htql/login.php">Máy chủ 01</a> hoặc <a href="https://dkmonhoc.ctu.edu.vn/htql/login.php">Máy chủ 02</a>.</div>-->
					
					</div>
                </td>
                <td width="40" align="center" valign="top">&nbsp;</td>
                <td id="module-thongbao" align="left" valign="top">
                    <ul class="thongbao"> 
					<li> 
						<span  style="color:red;">1. Thông báo bảo trì hệ thống đăng ký môn học từ 18:00 26/03/2025 đến 07:00 ngày 27/03/2025.</span>
					</li>
					<li> 
						<a  href="file/LICH_GDQP_K50_HK3_2024_2025.pdf" target="_blank">2. Lịch học GDQP&AN khóa 50 học kỳ 3, năm học 2024-2025</a>
					</li>
					<li> 
						<a  href="file/CV709_Ke_hoach_giang_day_va_DKHP_HK3_2024-2025.pdf" target="_blank">3. Thông báo kế hoạch giảng dạy và đăng ký học phần HK3, năm học 2024-2025</a>
					</li>
					<li> 
						<a  href="file/CV529_TB_DuaDon_SV_K50_Hoc_QPAN_DOT4_HK2_2024_2025.pdf" target="_blank">4. TB đưa, đón SV K50 học thực hành GDQP đợt 4 (đợt cuối), học kỳ 2 năm học 2024-2025</a>
					</li>
					<li> 
						<a  href="file/CV262_TB_DuaDon_SV_K50_Hoc_QPAN_DOT3_HK2_2024_2025.pdf" target="_blank">5. TB đưa, đón SV K50 học thực hành GDQP đợt 3, học kỳ 2 năm học 2024-2025</a>
					</li>
					<li> 
						<a  href="file/65_TB_Xoa_Lop_HP_HK2_2024_2025_DOTCUOI.pdf" target="_blank">6. Thông báo xóa lớp học phần HK2, năm học 2024-2025 (Đợt 2)</a>
					</li>
					<li> 
						<a  href="file/CV37_TB_DuaDon_SV_K50_Hoc_QPAN_DOT2_HK2_2024_2025.pdf" target="_blank">7. TB đưa, đón SV K50 học thực hành GDQP đợt 2, học kỳ 2 năm học 2024-2025</a>
					</li>
					<li> 
						<a  href="file/CV38_mo_lai_website_nhap_ke_hoach_hoc_tap.pdf" target="_blank">8. Thông báo mở lại website nhập KHHT đợt 1 năm 2025</a>
					</li>
					<li> 
						<a  href="file/CV4959_TB_DuaDon_SV_K50_Hoc_QPAN_DOT1_HK2_2024_2025.pdf" target="_blank">9. TB đưa, đón SV K50 học thực hành GDQP đợt 1, học kỳ 2 năm học 2024-2025</a>
					</li>
					<li> 
						<a  href="file/4813_TB_Xoa_Lop_HP_HK2_2024_2025_DOT1.pdf" target="_blank">10. Thông báo xóa lớp học phần HK2, năm học 2024-2025 (Đợt 1)</a>
					</li>					
					<li> 
						<a  href="file/LICH_GDQP_K50_HK2_2024_2025.pdf" target="_blank">11. Lịch học GDQP&AN khóa 50 học kỳ 2, năm học 2024-2025</a>
					</li>
					<li> 
						<a href="file/Kehoach_TN_2025.pdf" target="_blank">12. Kế hoạch xét và phát bằng tốt nghiệp đại học chính quy năm 2025</a>
					</li>
					<li> 
						<a style="color:red;" href="file/Video_HDSV_DKMH_WEB.mp4" target="_blank">13. Hướng dẫn sinh viên đăng ký môn học trên hệ thống mới (WEB)</a>
					</li>
					<li> 
						<a style="color:red;"  href="file/Video_HDSV_DKMH_MyCTUs.mp4" target="_blank">14. Hướng dẫn sinh viên đăng ký môn học trên hệ thống mới (App MyCTUs)</a>
					</li>
					<li><a href="file/CV4200_Ke_hoach_giang_day_va_DKHP_HK2_2024-2025.pdf" target="_blank"> 
								15.  Thông báo kế hoạch giảng dạy và đăng ký học phần HK2, 2024-2025</a>
					</li>
					<li><a href="file/CV3882_dieu_chinh_KHGD_HK1_24_25.pdf" target="_blank"> 
								16. Thông báo điều chỉnh KHGD, học tập học kỳ 1 năm học 2024-2025</a>
					</li>
					<li><a href="file/CV3701_TB_SV_khoa_50_hoc_GDQP&AN_tai_HA_HK1_2024-2025_dot_4.pdf" target="_blank"> 
								17. TB đưa, đón SV K50 học thực hành GDQP đợt 4 (đợt cuối), học kỳ 1 năm học 2024-2025</a>
					</li>
					<li><a href="file/CV3468_TB_SV_khoa_50_hoc_GDQP&AN_tai_HA_HK1_2024-2025_dot_3.pdf" target="_blank"> 
								18. TB đưa, đón SV K50 học thực hành GDQP đợt 3, học kỳ 1 năm học 2024-2025</a>
					</li>
					<li><a href="file/CV3310_TB_SV_khoa_50_hoc_GDQP&AN_tai_HA_HK1_2024-2025_dot_2.pdf" target="_blank"> 
								19. TB đưa, đón SV K50 học thực hành GDQP đợt 2, học kỳ 1 năm học 2024-2025</a>
					</li>
					<li><a href="file/CV3162_TB_SV_khoa_50_hoc_GDQP&AN_tai_HA_HK1_2024-2025_dot_1.pdf" target="_blank"> 
								20. TB đưa, đón SV K50 học thực hành GDQP đợt 1, học kỳ 1 năm học 2024-2025</a>
					</li>
					<li><a href="file/CV2962_mo lai website nhap ke hoach hoc tap.pdf" target="_blank"> 
								21. Thông báo mở lại website nhập KHHT đợt 2 năm 2024</a>
					</li>
					<li><a href="file/Lich_hoc_Giao_duc_QP&AN_khoa_50_hoc_ky_1_2024-2025.pdf" target="_blank"> 
								22. Lịch học GDQP&AN học kỳ 1, năm học 2024-2025 (khóa 50)</a>
					</li>
					<li><a href="file/CV2939_xoa_cac_lop_HP_so_luong_khong_du_mo_lop_HK1_2024_2025_dot_2.pdf" target="_blank"> 
								23. Thông báo xóa lớp học phần HK1, năm học 2024-2025 (Đợt cuối)</a>
					</li>
					<li><a href="file/CV2564_xoa_cac_lop_HP_so_luong_khong_du_mo_lop_HK1_2024_2025.pdf" target="_blank"> 
								24. Thông báo xóa lớp học phần HK1, năm học 2024-2025 (Đợt 1)</a>
					</li>
					<li><a href="file/CV1811_ke_hoach_giang_day_va_dang_ky_hoc_phan_hoc_ky_1_nam_hoc_2024_2025.pdf" target="_blank"> 
								25.Thông báo kế hoạch giảng dạy và đăng ký học phần HK1, năm học 2024-2025</a>
					</li>
				<!--	<li><a href="file/CV1804_TB_SV_khoa_49_hoc_GDQP&AN_tai_HA_HK3_2023-2024_dot_2.pdf" target="_blank"> 
								.TB đưa, đón SV K49 học thực hành GDQP đợt cuối, học kỳ 3 năm học 2023-2024</a>
					</li>
					<li><a href="file/CV1635_TB_SV_khoa_49_hoc_GDQP&AN_tai_HA_HK3_2023-2024_dot_1.pdf" target="_blank"> 
								.TB đưa, đón SV K49 học thực hành GDQP đợt 1, học kỳ 3 năm học 2023-2024</a>
					</li>
					<li><a href="file/CV1560_xoa_cac_lop_HP_so_luong_khong_du_mo_lop_HK3_2023_2024.pdf" target="_blank"> 
								.Thông báo xóa lớp học phần HK3, năm học 2023-2024 (Đợt 1)</a>
					</li>
					<li><a href="file/Lich_hoc_Giao_duc_QP&AN_khoa_49_hoc_ky_3_2023-2024.pdf" target="_blank"> 
								.Thông báo về Lịch học GDQP&AN khóa 49 học kỳ 3, năm học 2023-2024</a>
					</li>
					<li><a href="file/CV1047_dieu_chinh_ke_hoach_GD_HK2_2023_2024.pdf" target="_blank"> 
								.Thông báo về việc chuyển đổi phòng học 206/KH, 207/KH và 208/KH (học kỳ 2, năm học 2023-2024)</a>
					</li>
					<li><a href="file/CV885_KHGD_va_dang_ky_HP_HK3_nam_hoc_2023_2024.pdf" target="_blank"> 
								.Thông báo kế hoạch giảng dạy và đăng ký học phần HK3, 2023-2024</a>
					</li>
					<li><a href="file/CV733_TB SV khoa 49 hoc GDQP&AN tai HA HK2 2023-2024_Dot 5.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 5 (đợt cuối), học kỳ 2 năm học 2023-2024</a>
					</li>
					<li><a href="file/CV520_TB_SV_khoa_49_hoc_GDQP&AN_tai_HA_HK2_2023-2024_Dot_4.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 4, học kỳ 2 năm học 2023-2024</a>
					</li>
					<li><a href="file/CV224_TB_SV_khoa_49_hoc_GDQP&AN_tai_HA_HK2_2023_2024_Dot_3.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 3, học kỳ 2 năm học 2023-2024</a>
					</li>
					<li><a href="file/CV03_mo_lai_website_nhap_ke_hoach_hoc_tap.pdf" target="_blank"> 
								.Thông báo mở lại website kế hoạch học tập</a>
					</li>
					<li><a href="file/CV37_TB SV khoa 49 hoc GDQP tai HA HK2 2023-2024_Dot 2.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 2, học kỳ 2 năm học 2023-2024</a>
					</li>
					<li><a href="file/CV13_xoa cac lop HP so luong khong du mo lop HK2_2023_2024.pdf" target="_blank"> 
								.Thông báo xóa lớp học phần HK2, năm học 2023-2024 (Đợt cuối)</a>
					</li>
					<li><a href="file/CV4777_DuaDon_SV_K49_Hoc_QPAN_DOT1_HK2_2023_2024.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 1, học kỳ 2 năm học 2023-2024</a>
					</li>
					<li><a href="file/CV4737_xoa cac lop hoc phan co si so khong du mo lop HK2_2023_2024.pdf" target="_blank"> 
								.Thông báo xóa lớp học phần HK2, năm học 2023-2024 (Đợt 1)</a>
					</li>
					<li><a href="file/Kehoach_TN_2024.pdf" target="_blank"> 
								.Thông báo kế hoạch xét và phát bằng tốt nghiệp đại học chính quy 2024</a>
					</li>
					<li><a href="file/LICH_HOC_GDQP_HK2_2023_2024_K49.pdf" target="_blank"> 
								.Thông báo lịch học GDQP&AN khóa 49 học kỳ 2, năm học 2023-2024</a>
					</li>
					<li><a href="file/CV4025_KHGD va dang ky HP HK2, nam hoc 2023_2024.pdf" target="_blank"> 
								.Kế hoạch giảng dạy và đăng ký học phần HK2, 2023-2024</a>
					</li>
					<li><a href="file/CV3865_TB dua don SV K49 hoc thuc hanh GDQP HK1 2023-2024_dot 4.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 4 học kỳ 1, năm học 2023-2024</a>
					</li>
					<li><a href="file/CV3645_TB dua don SV K48 hoc thuc hanh GDQP HK1 2023-2024_dot 3.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 3 học kỳ 1, năm học 2023-2024</a>
					</li>
					<li><a href="file/CV3423_TB dua don SV K48 hoc thuc hanh GDQP HK1 2023-2024_dot 2.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 2 học kỳ 1, năm học 2023-2024</a>
					</li>
					<li><a href="file/3256.TB hoc GDQP&AN K49 hoc ky 1, nam hoc 2023_2024 (Dot 1).pdf" target="_blank"> 
								.Thông báo đưa, đón SV K49 học thực hành GDQP đợt 1 học kỳ 1, năm học 2023-2024</a>
					</li>
					<li><a href="file/2023-06-20_so_2216.ĐHCT-TC_-_Muc_hoc_phi_nam_hoc_2023-2024_(thay_the_1010.ĐHCT_TC).pdf" target="_blank"> 
								.Thông báo mức học phí năm học 2023-2024</a>
						</li>
					<li><a href="file/Lich hoc Giao duc quoc phong va AN K49_HK1_2022_2023.pdf" target="_blank"> 
								.Thông báo lịch học GDQP&AN khóa 49 học ký 1, năm học 2023-2024</a>
					</li>
					<li><a href="file/CV3057_mo lai website nhap KHHT HK2_HK3 NH 2023_2024.pdf" target="_blank"> 
								.Thông báo mở lại website kế hoạch học tập</a>
						</li>
					<li><a href="file/Xoa HP dot HK1 2023 2024 (dot 2).pdf" target="_blank"> 
								.Thông báo xóa lớp học phần HK1, năm học 2023-2024 (Đợt 2)</a>
						</li>					
					<li><a href="file/CV2592_xoa_cac_lop_hoc_phan_co_si_so_khong_du_lop_HK1_2023_2024.pdf" target="_blank"> 
							.Thông báo xóa lớp học phần HK1, năm học 2023-2024 (Đợt 1)</a>
					</li>
					<li><a href="file/CV1883_KeHoachGiangDayVaDangKyHocphan_HK1_2023_2024.pdf" target="_blank"> 
							.Thông báo kế hoạch giảng dạy và đăng ký học phần HK1, 2023-2024</a>
					</li>
					<li><a href="file/CV1855_TB dua don SV K48 hoc thuc hanh GDQP HK3 2022-2023_dot 2 (dot cuoi).pdf" target="_blank"> 
								.Thông báo đưa, đón SV K48 học thực hành GDQP đợt 2 (đợt cuối) học kỳ 3, năm học 2022-2023</a>
						</li>
					<li><a href="file/CV1767_xoa cac lop hoc phan co si so khong du lop HK3_2022_2023.pdf" target="_blank"> 
								.Thông báo xóa lớp học phần HK3, năm học 2022-2023 (Đợt 1)</a>
						</li>
						
						<li><a href="file/CV1615_TB dua don SV K48 hoc thuc hanh GDQP HK3 2022-2023_dot 1.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K48 học thực hành GDQP đợt 1 học kỳ 3, năm học 2022-2023</a>
						</li>
					<li><a href="file/Lich_hoc_GDQP_va_An_Ninh_khoa_48_HK3_2022_2023_Dieu_Chinh.pdf" target="_blank"> 
								.Thông báo lịch học GDQP&AN khóa 48 học kỳ 3, năm học 2022-2023 (Điều chỉnh)</a>
						</li>
					 <li><a href="file/Lich hoc GDQP va An Ninh khoa 48_HK3 2022_2023.pdf" target="_blank"> 
								.Thông báo lịch học GDQP&AN khóa 48 học kỳ 3, năm học 2022-2023</a>
						</li> 
					<li><a href="file/CV744_KHGD va đang ky HP HK3 nam hoc 2022_2023-1.pdf" target="_blank"> 
								.Thông báo kế hoạch giảng dạy và đăng ký học phần HK3, 2022-2023...</a>
						</li>
					<li><a href="file/CV723_TB dua don SV K48 hoc thuc hanh GDQP HK2 2022-2023_dot 5.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K48 học thực hành GDQP đợt 5 (đợt cuối) học kỳ 2, năm học 2022-2023.</a>
						</li>
						
					<li><a href="file/CV486_TB dua don SV K48 hoc thuc hanh GDQP HK2 2022-2023_dot 4.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K48 học thực hành GDQP đợt 4 học kỳ 2, năm học 2022-2023.</a>
						</li>
						
					<li><a href="file/CV320_TB dua don SV K48 hoc thuc hanh GDQP HK2 2022-2023_dot 3.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K48 học thực hành GDQP đợt 3 học kỳ 2, năm học 2022-2023.</a>
						</li>
					 <li><a href="file/CV39_TB dua don SV K48 hoc thuc hanh GDQP HK2 2022-2023_dot 2.pdf" target="_blank"> 
								.Thông báo đưa, đón SV K48 học thực hành GDQP đợt 2 học kỳ 2, năm học 2022-2023.</a>
						</li>
						 <li><a href="file/CV40_Mo lai website nhap KHHT.pdf" target="_blank"> 
								.  Thông báo mở lại website KHHT.</a>
						</li>
						
					<li><a href="file/CV07_xoa_cac_lop_HP_co_si_so_khong_du_mo_lop_HK2,nam_hoc_2022_2023_(dot_cuoi).pdf" target="_blank"> 
                                . Thông báo xóa các lớp học phần HK2, năm học 2022-2023 (Đợt cuối).</a></li>
                        </li>
						<li><a href="file/CV4033_xoa_cac_lop_HP_co_si_so_lop_khong_du_mo_lop_HK2_NH_2022_2023.pdf" target="_blank"> 
                                . Thông báo xóa các lớp học phần HK2, năm học 2022-2023 (Đợt 1).</a></li>
                        </li>
						<li><a href="file/CV4043_TB_dua_don_SV_K48_hoc_thuc_hanh_GDQP_HK2_2022_2023_dot_1.pdf" target="_blank"> 
                                . Thông báo đưa đón SV khóa 48 học thực hành học phần GDQP&AN học kỳ 2, năm học 2022-2023.</a></li>
                        </li>
						<li><a href="file/Lich hoc GDQP va An Ninh khoa 48_HK2 2022_2023.pdf" target="_blank"> 
                                . Thông báo Lịch học GDQP&AN học kỳ 2 năm học 2022-2023.</a></li>
                        </li>
						<li><a href="file/CV3519_TB_dua_don_SV_K48_hoc_thuc_hanh_GDQP_HK1_2022_2023_dot_4.pdf" target="_blank"> 
                                . Thông báo đưa, đón SV K48 học thực hành GDQP đợt 4 (đợt cuối), học kỳ 1, năm học 2022-2023.</a></li>
                        </li>
						<li><a href="file/CV3470_KH_giang_day_va_dang_ky_HP_HK2_2022_2023.pdf" target="_blank"> 
                                . Thông báo kế hoạch giảng dạy và đăng ký học phần HK2, 2022-2023.</a></li>
                        </li>
						<li><a href="file/CV3369_TB_dua_don_SV_K48_hoc_thuc_hanh_GDQP_HK1_2022_2023_dot_3.pdf" target="_blank"> 
                                . Thông báo đưa, đón SV K48 học thực hành GDQP đợt 3, học kỳ 1 năm học 2022-2023.</a></li>
                        </li>
						<li><a href="file/CV3194_TB_dua_don_SV_K48_hoc_thuc_hanh_GDQP_HK1_2022-2023_dot_2.pdf" target="_blank"> 
                                . Thông báo đưa, đón SV K48 học thực hành GDQP đợt 2, học kỳ 1 năm học 2022-2023.</a></li>
                        </li>
						<li><a href="file/CV3056_TB_dua_don_SV_K48_hoc_thuc_hanh_GDQP_HK1_2022-2023_dot_1.pdf" target="_blank"> 
                                . Thông báo đưa, đón SV K48 học thực hành GDQP đợt 1, học kỳ 1 năm học 2022-2023.</a></li>
                        </li>
						<li><a href="file/Kehoach_TN_2022_dot3lan2.pdf" target="_blank"> 
                                . Thông báo kế hoạch xét và phát bằng tốt nghiệp Đợt 3, lần 2 năm 2022.</a></li>
                        </li>
                        <li><a href="file/CV2718_DHCT_DT_31_08_2022_TB_Mo_WEBSITE_DieuChinh_KHHT_Dot2_2022.pdf" target="_blank"> 
                                . Thông báo mở lại website lập kế hoạch học tập đợt 2 2022.</a></li>
                        </li>
                        <li><a href="file/LICH_HOC_GDQP&AN_HK1_2022_2023_K48.pdf" target="_blank"> 
                                . Lịch học GDQP-AN KHÓA 48 HK1 2022-2023.</a>
                        </li>
                        <li><a href="file/CV2536_xoa cac lop HP HK1 2022_2023_dot 2.pdf" target="_blank"> 
                                . Thông báo xóa lớp học phần HK1, năm học 2022-2023 (Đợt cuối).</a>
                        </li>
                        <li><a href="file/CV2169_xoa cac lop HP khong mo lop HK1 22_23.pdf" target="_blank"> 
                                . Thông báo xóa lớp học phần HK1, năm học 2022-2023 (Đợt 1).</a>
                        </li>
                        <li><a href="file/CV1649_KH giang day va dang ky HP HK1 2022_2023_new.pdf" target="_blank"> 
                                . Thông báo kế hoạch giảng dạy và đăng ký học phần HK1, 2022-2023.</a>
                        </li>
                        <li><a href="file/CV1559_TB dua don SV K47 hoc thuc hanh GDQP HK3 2021-2022_dot 2.pdf" target="_blank"> 
                                . Thông báo đưa đón sinh viên K47 học GDQP&AN - HK3, 2021-2022 (Đợt cuối).</a>
                        </li>
                        
                        <li><a href="file/CV1405_TB dua don SV K47 hoc thuc hanh GDQP HK3 2021-2022_dot 1.pdf" target="_blank"> 
                                . Thông báo đưa đón sinh viên K47 học GDQP&AN - HK3, 2021-2022 (Đợt 1).</a>
                        </li>
                        <li><a href="file/CV1515_xoa cac lop HP khong mo lop HK3 21_22_dot 2.pdf" target="_blank"> 
						. Thông báo xóa lớp học phần HK3, năm học 2021-2022 (Đợt cuối).</a>
                                        </li>
                        <li><a href="file/CV1374_xoa cac lop HP khong mo lop HK3 21_22.pdf" target="_blank"> 
						. Thông báo xóa lớp học phần HK3, năm học 2021-2022 (Đợt 1).</a>
                                        </li>
                        <li><a href="file/Lich hoc GDQP_AN HK3 2021_2022.pdf" target="_blank"> 
						. Lịch học GDQP-AN KHÓA 47 HK3 2021-2022.</a> 
                                        </li>
                        <li><a href="file/HUONGDANSUDUNG_CBTRACUUHOCPHAN.pdf" target="_blank">
                                            . Hướng dẫn giảng viên tra cứu học phần mở trong học kỳ.</a>
                                    </li> 
                        <li><a href="file/HUONGDANSUDUNG_SVTRACUUHOCPHAN.pdf" target="_blank">
						. Hướng dẫn sinh viên cứu học phần mở trong học kỳ.</a>
                                        </li> -->
                        <li><a href="file/2022-02-24 số 376.ĐHCT-TC - Mức học phí năm học 2022-2023 (K48).pdf" target="_blank"> 
                                26. Thông báo mức học phí năm học 2022-2023.</a>
                        </li>
                        <li><a href="file/2021-03-19 số 481.ĐHCT-TC - Mức học phí năm học 2021-2022 (K47).pdf" target="_blank"> 
                                27. Thông báo mức học phí năm học 2021-2022.</a>
                        </li>
 <!--                       <li><a href="file/CV880_KH giang day va dang ky HP HK3 2021_2022.pdf" target="_blank"> 
                                . Thông báo kế hoạch giảng dạy và đăng ký học phần HK3, 2021-2022.</a>
                        </li>
                        <li><a href="file/CV369_TB dua don SV K47 hoc thuc hanh GDQP HK2 2021-2022_dot 4.pdf" target="_blank"> 
                                . Thông báo đưa đón sinh viên K47 học GDQP&AN - HK2, 2021-2022 (Đợt 4).</a>
                        </li>
                        <li><a href="file/CV234_TB dua don SV K47 hoc thuc hanh GDQP HK2 2021-2022(Dot3).pdf" target="_blank"> 
                                . Thông báo đưa đón sinh viên K47 học GDQP&AN - HK2, 2021-2022 (Đợt 3).</a>
                        </li>-->
<!--                        <li><a href="file/CV121_mo lai website nhap ke hoach hoc tap.pdf" target="_blank"> 
                                . Thông báo mở lại website nhập KHHT.</a>
                        </li>-->
<!--                        <li><a href="file/CV119_dieu chinh ke hoach giang day HK2 2021-2022.pdf" target="_blank"> 
                                . Thông báo điều chỉnh KHGD HK2, 2021-2022.</a>
                        </li>-->
<!--                        <li><a href="file/CV120_TB dua don SV K47 hoc thuc hanh GDQP HK2 2021-2022.pdf" target="_blank"> 
                                . Thông báo đưa đón sinh viên K47 học GDQP&AN - HK2, 2021-2022 (Đợt 2).</a>
                        </li>-->
<!--                        <li><a href="file/CV55_xoa ca lop HP HK2 2021_2022_dotcuoi.pdf" target="_blank"> 
                                . Thông báo xóa lớp học phần HK2, năm học 2021-2022 (Đợt cuối).</a>
                        </li>
                        <li><a href="file/CV3618_xoa cac lop HP HK2 2021_2022.pdf" target="_blank"> 
                                . Thông báo xóa lớp học phần HK2, năm học 2021-2022.</a>
                        </li>-->
<!--                        <li><a href="file/CV2460_TB tiep tuc trien khai KH hoc GDQP dot2 HK3 2020-2021.pdf" target="_blank">
                                . Thông báo tiếp tục triển khai học GDQP&AN đợt 2 Học kỳ 3, năm học 2020-2021</a>
                        </li>-->
<!--                       <li><a href="file/Kehoach_TN_2022.pdf" target="_blank">
						. Kế hoạch xét và phát bằng tốt nghiệp năm 2022. </a></li>
                       <li><a href="file/LICH_HOC_GDQP_K47_HK2_2021_2022_V1.pdf" target="_blank"> 
						. Lịch học GDQP Khóa 47 HK2 2021-2022.</a>
                                        </li>-->
                        
<!--                        <li><a href="file/CV2195_KHGD_DKHP_HK2_2021_2022.pdf" target="_blank"> 
						. Thông báo kế hoạch giảng dạy và đăng ký học phần HK2, 2021-2022.</a>
                                        </li>-->
<!--                        <li><a href="file/CV1794_molaiwebsitenhapKHTH.pdf" target="_blank"> 
						. Thông báo mở lại website nhập KHHT.</a>
                                        </li>-->
<!--                        <li><a href="file/Lich hocGDQPkhoa47_HK1_2021_2022.pdf" target="_blank"> 
						. Lịch học GDQP Khóa 47 HK1 2021-2022.</a>
                                        </li>-->
<!--                        <li><a href="file/2021_CV1691_xoacaclopHPHK1_21_22_dot2.pdf" target="_blank"> 
						. Thông báo xóa lớp học phần HK1, năm học 2021-2022 (Đợt cuối).</a>
                                        </li>-->
<!--                        <li><a href="#" target=""> 
						. <span id="">THÔNG BÁO:</span> <br>
                            Học kỳ 1, năm học 2021-2022, sinh viên được quyền Xóa học phần (không đóng học phí) đến hết ngày 19/9/2021, việc Rút học phần (phải đóng học phí) tiếp tục được thực hiện đến hết ngày 03/10/2021 đối với kết quả đăng ký học phần của học kỳ
                            
                            </a>
                                        </li>-->
                        
<!--                        <li><a href="file/2021_CV1597xoacaclopHPHK1NH2021_2022dot1.pdf" target="_blank"> 
						. Thông báo xóa lớp học phần HK1, năm học 2021-2022 (Đợt 1).</a>
                                        </li>-->
<!--                        <li><a href="file/GDQP_dot2_HK3_2020_2021.pdf" target="_blank"> 
						. Thông báo đưa, đón SV học GDQP K46 đợt 2 (đợt cuối), HK3, năm học 2020-2021.</a>
                                        </li>-->
<!--                        <li><a href="http://dkmh2.ctu.edu.vn/tracuu/demo.php" target="_blank"> 
						. Trang tra cứu học phần mở trong HK1, 2021-2022.</a>
                                        </li>-->
<!--                        <li><a href="file/CV1279_xoalopHK320_21_dot2.pdf" target="_blank"> 
						. Thông báo xóa lớp học phần HK3, năm học 2020-2021 (Đợt cuối).</a>
                                        </li>-->
<!--                        <li><a href="file/CV1189_xoacaclopHPHK320_21.pdf" target="_blank"> 
						. Thông báo xóa lớp học phần HK3, năm học 2020-2021 (Đợt 1).</a>
                                        </li>-->
<!--                        <li><a href="file/TB1112_TBhocGDQPdot1_HK320202021.pdf" target="_blank"> 
						. Thông báo đưa, đón SV học GDQP K46 đợt 1, HK3, năm học 2020-2021.</a>
                                        </li>-->
<!--                        <li><a href="file/LichhocGDQPHK32020_2021.pdf" target="_blank"> 
						. Lịch học học phần giáo dục quốc phòng và an ninh HK3, năm học 2020-2021.</a>
                                        </li>-->
<!--                        <li><a href="https://dkmh2.ctu.edu.vn/tracuu/demo.php" target="_blank">
                                . Trang tra cứu học phần mở trong HK3, 2020-2021.</a>
                        </li>-->
                        
<!--                        <li><a href="file/CV721_dangkyhocphanHK32020_2021.pdf" target="_blank">
                                . Thông báo kế hoạch giảng dạy và đăng ký học phần học kỳ 3, năm học 2020-2021.</a>
                        </li>                        -->
<!--                        <li><a href="file/CV489_dieuchinhKHGDHK2_20_21.pdf" target="_blank">
                                . Thông báo điều chỉnh KHGD HK2, 2020-2021 (thay đổi phòng học để phục vụ bầu cử ngày 22/5/2021 và 23/5/2021).</a>
                        </li>
                        
                        <li><a href="https://daa.ctu.edu.vn/images/upload/VanBan/QCHV_2021.pdf" target="_blank">
						. Quy định công tác học vụ từ HK 1 2021-2022.</a></li>
                        
                       <!-- <li><a href="file/MucHocPhi_2021.pdf" target="_blank">
                                . Công văn quy định mức học phí năm học 2020-2021.</a>
                        </li>
                        						
                        <li><a href="https://gs.ctu.edu.vn/tkb/1119-thong-bao-dang-ky-hoc-phan-danh-sach-hoc-phan-mo-va-thoi-khoa-bieu-trong-hoc-ky-1-nam-hoc-2020-2021-trinh-do-thac-si-danh-cho-hoc-vien-cao-hoc-cac-khoa.html" target="_blank">
						. Thông báo đăng ký học phần, danh sách học phần mở và thời khóa biểu trong học kỳ 1 năm học 2020-2021 trình độ thạc sĩ dành cho học viên cao học các khóa.</a>
                                        </li> -->
                        
<!--                        <li><a href="file/Kehoach_TN_2020_dot3_dc.pdf" target="_blank">
						. Điều chỉnh kế hoạch xét tốt nghiệp đợt 3 năm 2020.</a>
                                        </li>-->
                        
<!--					<li><a href="file/TBThuHocPhiNHHDBank.pdf" target="_blank">
						. Thông báo thu học phí qua Ngân hàng HDbank. </a></li>				-->
					
					<li>28. Mức học phí chất lượng cao <a href="file/CLC_2016.pdf" target="_blank">năm 2016</a>, <a href="file/CTTT_CLC_2017.pdf" target="_blank">năm 2017</a>,<a href="file/CTTT_CLC_2018.pdf" target="_blank"> năm 2018. </a>, <a href="file/CTTT_CLC_2019.pdf" target="_blank"> năm 2019. </a>, <a href="file/CTTT_CLC_2020.pdf" target="_blank"> năm 2020. </a></li>
                                        
                                        <li>29. Quy định mức học phí áp dụng cho <a href="https://dfa.ctu.edu.vn/images/upload/VBCapTruong/MucHocPhi_1819.pdf" target="_blank">năm học 2018-2019</a>, <a href="file/MucHocPhi_1920.pdf" target="_blank">năm 2019-2020</a></li>
                                        
					<!--<li><a href="https://www.ctu.edu.vn/thong-bao/1235-ra-soat-bo-sung-nguon-nhan-luc-giang-day-hoc-phan.html" target="_blank">
						. Công văn 2493 về rà soát bổ sung nguồn lực giảng dạy học phần. </a></li>	-->									
					<li><a href="https://tansinhvien.ctu.edu.vn/hoc-tap/so-do-nha-hoc-ky-hieu-phong-hoc" target="_blank"> 
						30. Sơ đồ nhà học - Ký hiệu phòng học. </a></li>							
<!--					<li><a href="file/MauDangKyDichVuHocPhi.doc" target="_blank">
						. Mẫu đăng ký sử dụng dịch vụ thanh toán tiền học phí tự động qua tài khoản. </a></li>-->
						<li><a href="file/DanhSachMayTinh.pdf" target="_blank">
						31. Danh sách các khu vực máy tính phục vụ Đăng ký học phần.</a></li>
					
					<!--
     <li><a href="http://bit.ly/2M1VVuG" target="_blank">
						32. Quy định công tác học vụ từ năm học 2019-2020.</a></li>		
						
    <li><a href="file/CV847_dieuchinhKHGDHK2_2020_2021.pdf" target="_blank">
	33. Thông báo điều chỉnh KHGD HK2, 2020-2021 (phục vụ bầu cử ngày 21, 22 và 23/5/2021).</a>
</li>
<li><a href="file/CV724_TBhocGDQPdot5HK2_2020_2021_dieuchinh.pdf" target="_blank">
	34. Thông báo (điều chỉnh) đưa, đón SV K46 học GDQP đợt 5 (đợt cuối), học kỳ 2, năm học 2020-2021.</a>
</li>
<li><a href="file/CV515_TBhocGDQPdot4_HK2_2020_2021.pdf" target="_blank">
	35. Thông báo đưa, đón SV học GDQP K46 đợt 4, HK2, năm học 2020-2021.</a>
</li>
<li><a href="file/LICHHOC_GDQP_HK2_2020_2021_K46.pdf" target="_blank">
	36. Lịch học Giáo dục quốc phòng và an ninh học kỳ 2, năm học 2020-2021.</a>
</li>
     <li><a href="file/CV684_TBhocGDQPdot5_HK220_21.pdf" target="_blank">
                                37. Thông báo đưa, đón SV học GDQP K46 đợt 5 (đợt cuối), HK2, năm học 2020-2021.</a>
                        </li>
     <li><a href="file/CV2392_GDQP_K46_DOT1_HK1_2020_2021.pdf" target="_blank">
                                38. Thông báo học GDQP đợt 1 học kỳ 1, năm học 2020-2021.</a>
                        </li>
                        <li><a href="file/CV36_molaiwebnhapKHHTHK12020_2021.pdf" target="_blank">
                                39. Thông báo mở lại website nhập KHHT.</a>
                        </li>
                        <li><a href="file/CV2135_xoacaclopHPkhongdumolopHK12020_2021dot2.pdf" target="_blank">
                                40. Thông báo xóa lớp học phần đợt cuối học kỳ 1, năm học 2020-2021.</a>
                        </li>
                        <li><a href="file/CV2067_xoalopHK1_2020_2021.pdf" target="_blank">
                                41. Thông báo xóa lớp học phần HK1, năm học 2020-2021 (Đợt 1).</a>
                        </li>
     <li><a href="file/CV2891_TBhocGDQPdot4_HK1_2020_2021.pdf" target="_blank">
						42. Thông báo sinh hoạt, đưa đón sinh viên khóa 46 học GDQP&AN đợt 4 (học kỳ 1, năm học 2020-2021) tại khu Hòa An</a></li>
                        <li><a href="file/LichhocGDQP_K46HK1_2020_2021_dieuchinhlan3.pdf" target="_blank">
						43. Thông báo lịch học GDQP K46 học kỳ 1, 2020-2021 (chỉnh lần 3)</a></li>
                        <li><a href="file/CV2689_TBduadonSVhocGDQP_dot3HK12020_2021.pdf" target="_blank">
						44. Thông báo đưa, đón học GDQP K46 đợt 3, học kỳ 1, năm học 2020-2021</a></li>
                        <li><a href="file/CV2535_TBhocGDQP_dot2_HK1_2020_2021.pdf" target="_blank">
						45. Thông báo đưa, đón học GDQP K46 đợt 2, học kỳ 1, năm học 2020 và Lịch học GDQP điều chỉnh.</a><br/><a href="file/LichhocGDQP_K46HK1_2020_2021_dieuchinhlan2.pdf" target="_blank"><i>(Xem chi tiết lịch học)</i></a></li>
     <li><a href="file/MucHocPhi_1920.pdf" target="_blank">
						46. Quy định mức học phí áp dụng cho năm học 2019-2020.</a></li>	
     <li><a href="file/CV1696_KHgiangdayHK12020_2021.pdf" target="_blank">
						47. Thông báo kế hoạch giảng dạy và đăng ký học phần HK1, 2020-2021.</a>
                                        </li>
     <li><a href="file/Kehoach_TN_2020.pdf" target="_blank">
						48. Kế hoạch xét và phát bằng tốt nghiệp năm 2020. </a></li>
					
						
     <li><a href="https://dfa.ctu.edu.vn/images/upload/VBCapTruong/MucHocPhi_1819.pdf" target="_blank">
						49. Quy định mức học phí áp dụng cho năm học 2018-2019.</a></li>
     <li><a href="https://dkmh2.ctu.edu.vn/tracuu/demo.php" target="_blank">
						50. Trang tra cứu học phần mở trong HK1, 2020-2021.</a>
                                        </li>
     <li><a href="file/CV1906_LichthiDGNLTACTTT_CLC.pdf" target="_blank">
						51. Lịch thi đánh giá năng lực tiếng Anh (dành cho chương trình tiên tiến và chương trình chất lượng cao).</a>
     <li><a href="#">
						52. Nhà Trường xin thông báo đến toàn thể sinh viên: do từ chiều ngày 24/08/2020 đến tối ngày 25/08/2020, Hệ thống Thông tin tích hợp thực hiện việc bảo trì và sửa chữa, do đó <font color='red'>thời gian điều chỉnh kế hoạch học tập học kỳ 1 năm học 2020-2021 của Sinh viên sẽ được mở rộng thêm một ngày, thời hạn kết thúc mới là đến hết ngày <b>31/08/2020</b></font>.</a>
                        </li>
     <li><a href="file/CV1594_XoacaclopHPHK32019_2020.pdf" target="_blank">
						53. Thông báo xóa lớp học phần HK3, năm học 2019-2020 (Đợt cuối).</a>
                                        </li>
					<li><a href="file/GDQP_dot1_HK3_1920.pdf" target="_blank">
						54. Thông báo đưa, đón sinh viên học GDQP&AN đợt 1, học kỳ 3 năm học 2019-2020.</a>
					</li>
					<li><a href="file/CV1505_xoacaclopHPHK32019_2020.pdf" target="_blank">
						55. Văn bản xóa lớp học phần HK3, năm học 2019-2020.</a>
					</li>
					<li><a href="file/CV1190_TBkehocGDQPdot4HK22019_2020.pdf" target="_blank">
						56. Thông báo học GDQP&AN đợt 4 tại Hòa An, học kỳ 2 năm học 2019-2020.</a>
                                        </li>
					<li><a href="https://htql.ctu.edu.vn/tracuu" target="_blank">
						57. Công bố thời khóa biểu các lớp học phần mở trong học kỳ 3 2019-2020.</a>
                        </li>
					<li><a href="file/CV1015_hocphanThiDGNLtiengAnhCTTT_CLC.pdf" target="_blank">
						58. Thông báo học phần Thi đánh giá năng lực tiếng Anh (FL100H) dành cho chương trình tiên tiến và chương trình chất lượng cao.</a>
						
					</li>
					<li><a href="file/CV960_kehoachGDvadangkyHP_HK32019_2020.pdf" target="_blank">
						59. Thông báo kế hoạch giảng dạy và đăng ký học phần học kỳ 3, năm học 2019-2020.</a></li>
					<li><a href="file/Kehoach_TN_2020_dot2_dc.pdf" target="_blank">
						60. Kế hoạch điều chỉnh xét và phát bằng tốt nghiệp đợt 2 - năm 2020.</a></li>
					<li><a href="file/CV2371_KHGD_DKHP_HK2_2019_2020.pdf" target="_blank">
						61. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 2, 2019-2020. </a></li>	
					<li><a href="file/TB767_TB_hoc_GDQP_HK2_2019_2020_dot5.pdf" target="_blank">
						62. Thông báo học GDQP&AN đợt 5 (đợt cuối) , học kỳ 2 năm học 2019-2020.</a></li>
					
					<li><a href="file/CV649_TB_HOC_GDQP_DOT4_HK2_2019_2020.pdf" target="_blank">
						63. Thông báo học GDQP&AN đợt 4, học kỳ 2 năm học 2019-2020.</a>
                                        <br/>
                                        <a href="file/9DDdot4HK2K45.xls" target="_blank">
						&nbsp;&nbsp;&nbsp;&nbsp;(Lịch giảng dạy chi tiết cho từng đại đội)</a>
                                        </li>
					<li><a href="file/CV617_tiep_tuc_trien_khai_KHGD_khong_tap_trung_HK2_2019_2020.pdf" target="_blank">
						64. Tiếp tục triển khai kế hoạch giảng dạy không tập trung học kỳ 2 năm học 2019-2020</a></li>
					<li><a href="file/TB520_Hoc_GDQP_Dot3_HK2_2019_2020.pdf" target="_blank">
						65. Thông báo học GDQP&AN đợt 3, học kỳ 2 năm học 2019-2020</a></li>
					<li><a href="file/TB441_TB_hoc_GDQP_Dot2_HK2_19_20_dieu_chinh_lan_3.pdf" target="_blank">
						66. Thông báo kế hoạch học GDQP&AN đợt 2, 2019-2020 (điều chỉnh lần 3)</a></li>
					<li><a href="file/CV387_TrienKhai_KHGD_HK2_2019_2020.pdf" target="_blank">
						67. Triển khai kế hoạch giảng dạy Học kỳ 2, 2019-2020.</a></li>
					<li><a href="file/CV382_trienkhaiKHGDHK2_HK3_2019_2020_NEW.pdf" target="_blank">
						68. Thông báo điều chỉnh kế hoạch giảng dạy Học kỳ 2 và Học kỳ 3, 2019-2020.</a></li>
					<li><a href="file/CV_DuaDon_SV_K45_Hoc_QPAN_DOT2_HK2_2019_2020_(DIEUCHINH_LAN2)_V2_THANG3.pdf" target="_blank">
						69. Thông báo đưa đón sinh viên K45 học GDQP&AN - HK2, 2019-2020 (Đợt 2 điều chỉnh lần 2).</a></li>
						<li><a href="file/LichhocGDQP_HK2_2019_2020_dieuchinh.pdf" target="_blank">
						70. Lịch học GDQP K45 học kỳ 2, 2019 - 2020 (điều chỉnh).</a></li>
                        <li><a href="file/CV_27_mo_lai_website_nhap_KHHT.pdf" target="_blank">
						71. Thông báo mở lại website lập kế hoạch học tập đợt 1 năm 2020.</a></li>
                                        
                        <li><a href="file/TB_DKHP_HK2_2019_2020.pdf" target="_blank">
						72. Thông báo đăng ký học phần, danh sách học phần mở và thời khóa biểu trong học kỳ 2 năm học 2019-2020 trình độ thạc sĩ dành cho học viên cao học các khóa.</a></li>
					<li><a href="file/CV_256_TB_hoc_GDQP_HK2_19_20_dot3.pdf" target="_blank">
						. Thông báo đưa đón sinh viên K45 học GDQP&AN - HK2, 2019-2020 (Đợt 3).
						</a></li>
					<li><a href="file/CV_198_doi_lich_hoc_GDQP_Dot2_HK2_19_20.pdf" target="_blank">
						. Thông báo điều chỉnh kế hoạch học GDQP&AN đợt 2, HK2 năm học 2019-2020.
						</a></li>
					<li><a href="file/CV146_TB_hoc_GDQP_HK2_19_20_dot_2_doi_lich_hoc.pdf" target="_blank">
						. Thông báo đưa đón sinh viên K45 học GDQP&AN - HK2, 2019-2020 (Đợt 2 dời lịch học).
						</a></li> -->
					
					<!-- <li><a href="file/CV_2661_duadonSVhocGDQP_dot5_HK1_19_20.pdf" target="_blank">
						. Thông báo đưa đón sinh viên K45 học GDQP&AN - HK1, 2019-2020 (Đợt cuối).
						</a></li> -->
					<!-- <li><a href="file/DieuChinhKHGD_HK1_1920.pdf" target="_blank">
						. Thông báo điều chỉnh KHGD học kỳ 1, 2019-2020. </a></li> -->
					<!--  <li><a href="file/CV3007_TB_hoc_GDQP_dot1_HK2_2019_2020.pdf" target="_blank">
						. Thông báo đưa đón sinh viên K45 học GDQP&AN - HK2, 2019-2020 (Đợt 1).
						</a></li> -->
					<!--  <li><a href="file/KeHoachGiangDayVaDangKyHocphan_HK2_2019_2020(DieuChinh).pdf" target="_blank">
						. Thông báo "Chia nhóm và điều chỉnh thời gian" điều chỉnh kế hoạch học tập sinh viên khóa 44 và 45.
						</a></li> -->
					<!-- <li><a href="file/TB_Xoa_Lop_HP_HK2_1920_DOT1.pdf" target="_blank">
						. Thông báo xóa lớp học phần không đủ sĩ số mở lớp HK2, 2019-2020 (Đợt 1).
						</a></li> -->
					<!--
					<li><a href="file/CV2492_DuaDon_SV_K45_Hoc_QPAN_HK1_2019_2020.pdf" target="_blank">
						3. Thông báo đưa đón sinh viên K45 học GDQP HK 1, 2019-2020 (đợt 4). </a></li>
					<li><a href="file/TB_Mo_WEBSITE_DieuChinh_KHHT.pdf" target="_blank">
						4. Thông báo mở lại WEB nhập kế hoạch học tập, học kỳ 1, 2019-2020. </a></li>
					<li><a href="https://gs.ctu.edu.vn/images/upload/KHHT-DKHP/20182019/TBXoaHPsoluongdkit.pdf" target="_blank">
						4. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 1, 2019-2020 (SDH).</a></li>
					<li><a href="file/SacombankTayNamBo.ods" target="_blank">
						13. Danh sách mạng lưới Sacombank. </a></li>
					<li><a href="file/KeHoachGiangDayVaDangKyHocphanHK1_2019_2020.pdf" target="_blank">
					<li><a href="https://tinyurl.com/y2fyprmt" target="_blank">
						4 Thông báo đăng ký học phần bậc đào tạo thạc sĩ học kỳ 1 năm học 2019-2020.</a></li>
					<li><a href="http://dkmh2.ctu.edu.vn/tracuu/demo.php" target="_blank">
						2. Tra cứu các học phần mở trong học kỳ 1 năm học 2019-2020.</a></li>
					<li><a href="file/TB_Xoa_Lop_HP_HK3_1819(dot2).pdf" target="_blank">
						3. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 3, 2018-2019 (đợt 2).</a></li>
					<li><a href="file/TB_Xoa_Lop_HP_HK3_1819.pdf" target="_blank">
						3. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 3, 2018-2019.</a></li>
					<li><a href="file/KeHoachGiangDayVaDangKyHocphanHK2_2018_2019.pdf" target="_blank">
						7. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 2, 2018-2019. </a></li>	
					<li><a href="file/TB_Mo_WEBSITE_DieuChinh_KHHT_Dot1_2019.pdf" target="_blank">
						3. Thông báo mở lại hệ thống nhập kế hoạch học tập, học kỳ 2, 2018-2019. </a></li>	
					<li><a href="file/TB_Xoa_Lop_HP_HK2_1819_DOT2.pdf" target="_blank">
						3. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2018-2019 (đợt 2).</a></li>					
					<li><a href="file/TB_Xoa_Lop_HP_HK2_1819.pdf" target="_blank">
						5. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2018-2019 (đợt 1).</a></li>
					<li><a href="http://dkmh2.ctu.edu.vn/tracuu/demo.php" target="_blank">
						2. Tra cứu các học phần mở trong học kỳ 2 năm học 2018-2019.</a></li>
					<li><a href="https://goo.gl/8CWchv" target="_blank">
						4. Thông báo mở lại hệ thống nhập kế hoạch học tập bậc sau đại học, học kỳ 2, 2018-2019. </a></li>
					<li><a href="file/CV_1693_DieuChinhKHGD_KhuI.pdf" target="_blank">
						6. Thông báo điều chỉnh KHGD Khu I học kỳ 1, 2018-2019. </a></li>	
					<li><a href="file/KeHoachGiangDayVaDangKyHocphanHK1_2018_2019.pdf" target="_blank">
						6. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 1, 2018-2019. </a></li>
						<li><a href="file/LichHocGDQP_K43_hk3.pdf" target="_blank">
						5. Lịch học giáo dục quốc phòng khóa 43, học kỳ 3 năm học 2017-2018.</a></li>
					<li><a href="file/ThongBaoXoaLopHP_HK2_2017-2018(dot2).pdf" target="_blank">
						3. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2017-2018 (đợt 2).</a></li>					
					<li><a href="file/TBDieuChinhLichDayHK2_1718.pdf" target="_blank">
						4. Thông báo chuyển đổi lịch giảng dạy phục vụ kỳ thi thăng hạng CDNN giảng viên chính năm 2017.</a></li>					
					<li><a href="https://tinyurl.com/yc3rca9u" target="_blank">
						6. Thời gian đăng ký học phần và giảng dạy trình độ thạc sĩ và tiến sĩ, học kỳ 2, 2017-2018. </a></li>											
					<li><a href="file/LichHocGDQP_K43_hk2.pdf" target="_blank">
						7. Lịch học giáo dục quốc phòng khóa 43, học kỳ 2 năm học 2017-2018.</a></li>
					<li><a href="http://goo.gl/jgcQXJ" target="_blank">
						3. Tra cứu các học phần mở trong học kỳ 1 năm học 2017-2018 (SDH).</a></li>					
					<li><a href="file/DieuChinhP106C1.pdf" target="_blank">
						4. Điều chỉnh kế hoạch giảng dạy học kỳ 3, năm học 2016-2017 phục vụ sửa chữa phòng 106/C1.</a></li>					
					<li><a href="file/CV_Thong bao dua don sinh vien hoc GDQP_HK3_2016-2017.pdf" target="_blank">
						5. Thông báo đưa đón sinh viên học GDQP HK 3, năm học 2016-2017. </a></li>
					<li><a href="file/LICH_CHUYEN_PHONG_HT2.XLS" target="_blank">
						5. Thông báo thay đổi phòng học ở Hội trường 2. </a></li>						
					<li><a href="file/ThongBaoDoiPhongHoc.pdf" target="_blank">
						6. Thông báo thay đổi phòng học. </a></li>	
					<li><a href="file/TBxoalopHP_HK2_2016_2017.pdf" target="_blank">
						5. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2016-2017(Khoa Sau đại học).</a></li>
					<li><a href="file/ThongBaoXoaLopHP_HK2_2016-2017.pdf" target="_blank">
						6. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2016-2017.</a></li>
					<li><a href="file/ThongBaoMoLaiWEBSITEDieuChinhKHHT(Dot_1_Nam_2017).pdf" target="_blank">
						2. Thông báo mở lại hệ thống nhập KHHT đợt 1 năm 2017. </a></li>
					<li><a href="file/ThongBaoXoaLopHP_HK2_2016-2017(dot2).pdf" target="_blank">
						3. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2016-2017 (đợt 2).</a></li>
					<li><a href="http://gs.ctu.edu.vn/?p=5459" target="_blank">
						7. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 2, 2016-2017 (Khoa Sau đại học). </a></li>
					<li><a href="http://dkmh2.ctu.edu.vn/tracuu/demo.php" target="_blank">
						9. Tra cứu các học phần mở trong học kỳ 2 năm học 2016-2017.</a></li>					
					
					<li><a href="file/DSSV_K42DuocHoanTraHocPhi_HK1_1617.pdf" target="_blank">
						6. Danh sách sinh viên khóa 42 được hoàn trả học phí, học kỳ 1, 2016-2017. </a></li>
					<li><a href="file/TB_BSPH_HK1_1617.doc" target="_blank">
						9. Thông báo bổ sung quỹ phòng học, học kỳ 1, 2016-2017. </a></li>	
					
					
					<li><a href="http://gs.ctu.edu.vn/?p=4889" target="_blank">
						6. Thông báo đăng ký nhu cầu học phần Triết học ML606 nhóm ML11 giảng dạy vào thứ 7 chủ nhật.</a></li>
					<li><a href="http://gs.ctu.edu.vn/?p=4836" target="_blank">
						7. Thông báo xóa các lớp học phần có số lượng học viên đăng ký không đủ mở lớp học kỳ 1 năm học 2016-2017 (Khoa SDH).</a></li>
					<li><a href="file/TBthoigianDKHP_HK1_20162017.pdf" target="_blank">
						9. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 1, 2016-2017 (Khoa Sau đại học). </a></li>
					<li><a href="file/KeHoachGiangDay_DKHP_HK1_2016_2017.pdf" target="_blank">
						10. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 1, 2016-2017. </a></li>
					<li><a href="http://websrv2.ctu.edu.vn/dept/dfa/thongtin/vanban/muchocphi2015_2016.pdf" target="_blank">
						15. Quy định mức học phí áp dụng cho năm học 2015-2016.</a></li>
					<li><a href="file/LichHocGDQP_K41_HK3_15_16.pdf" target="_blank">
						13. Kế hoạch xét tốt nghiệp năm 2016. </a></li>
					
					<li><a href="file/TBChinhKHGD_KHCT.pdf" target="_blank">
						6. Thông báo đổi phòng học phục vụ sửa chữa nhà học Khoa KHCT hk3, 2015-2016. </a></li>	
					9. Lịch học Giáo dục Quốc Phòng khóa 41, HK 3, 2015-2016.</a></li>		
					<li><a href="file/KeHoachGiangDay_DKHP_HK3_2015_2016.pdf" target="_blank">
						10. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 3, 2015-2016. </a></li>
					<li><a href="http://www.ctu.edu.vn/upload/notice/2015/2015_2290_DHCT_DT.pdf" target="_blank">
						<li><a href="file/TBmohethongnhapKHHT_SDH.pdf" target="_blank">
						4. Thông báo mở lại hệ thống điều chỉnh KHHT bậc sau đại học.</a></li>
					<li><a href="file/ThongBaoXoaLopHP_HK3_2015-2016.pdf" target="_blank">
						5. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 3, 2015-2016.</a></li>
					
					<li><a href="file/ThongBaoMoLai_WEBSITE_dieu_chinh_KHHT_dot_1_nam_2016.doc" target="_blank">
						3. Thông báo mở lại website điều chỉnh KHHT (đợt 1 năm học 2015-2016).</a></li>
										
					<li><a href="file/ThongBaoXoaLopHP_HK2_2015-2016.pdf" target="_blank">
						4. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2015-2016 .</a></li>					
					<li><a href="http://gs.ctu.edu.vn/?p=3480" target="_blank">
						5. Tra cứu các học phần mở trong học kỳ 2 năm học 2015-2016 (Thạc sĩ và tiến sĩ).</a></li>
					<li><a href="http://gs.ctu.edu.vn/?p=3399" target="_blank">
						6. Lập kế hoạch học tập và đăng ký học phần cao học, NCS học kỳ 2 năm học 2015-2016 (Khoa Sau đại học). </a></li>
					
					<li><a href="file/ThongBaoXoaLopHP_HK1_2015-2016(sdh).pdf" target="_blank">
						8. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 1, 2015-2016 (SDH).</a></li>
					<li><a href="file/ThongBaoXoaLopHP_HK1_2015-2016.pdf" target="_blank">
						9. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 1, 2015-2016.</a></li>
					<li><a href="file/dsxoahp_HK1_2015-2016.xls" target="_blank">	
						10. Danh sách sinh viên xóa lớp học phần do không đủ sĩ số mở lớp theo quy định (Theo công văn số:1290 /ĐHCT-ĐT ngày 06/07/2015).</a></li>
					<li><a href="http://gs.ctu.edu.vn/?p=2810" target="_blank">
						11. Danh sách các học phần mở trong học kỳ 1 năm học 2015-2016 (Khoa Sau đại học).</a></li>		
					<li><a href="file/ThongBaoXoaLopHP_HK1_2015-2016(Dot2).pdf" target="_blank">
						6. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 1, 2015-2016 (đợt 2).</a></li>
					<li><a href="http://websrv2.ctu.edu.vn/dept/daa/index.php?option=com_content&view=article&id=636:k-hoch-xet-tt-nghip-t-2-va-3-nm-2015-&catid=116:tintndhcq&Itemid=379" target="_blank">
						14. Kế hoạch xét tốt nghiệp đợt 2 và 3 năm 2015. </a></li>-->
					
					<!--
					<li><a href="http://dkmh2.ctu.edu.vn/tracuu/demo.php" target="_blank">
						9. Tra cứu các học phần mở trong học kỳ 1 năm học 2015-2016.</a></li>
					<li>9. <b>Lưu ý:</b> Sinh viên các ngành học Giáo dục Quốc phòng-An ninh trong đợt 5 (từ ngày 13/4/2015 đến 08/5/2015) có nhu cầu đăng ký học phần trong học kỳ 3, năm học 2014-2015, vẫn tiến hành đăng ký theo “Kế hoạch giảng dạy và đăng ký học phần học kỳ 3, 2014-2015” đã công bố (công văn số 354/ĐHCT-ĐT) từ hệ thống máy tính và mạng wifi của Trung tâm Giáo dục Quốc phòng- An ninh tại Hòa An.</li>
					<li><a href="file/LichHocGDQP_K40_HK3_2014_2015.pdf" target="_blank">
						10. Lịch học giáo dục quốc phòng khóa 40, học kỳ 3 năm học 2014-2015.</a></li>
					<li><a href="file/KeHoachGiangDay_DKHP_HK3_2014_2015.pdf" target="_blank">
						8. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 3, 2014-2015. </a></li>
					<li><a href="file/CV_Thong bao dua don sinh vien hoc GDQP_HK3_2014-2015.pdf" target="_blank">
						6. Thông báo đưa đón sinh viên học GDQP HK 3, năm học 2014-2015. </a></li>
					<li><a href="file/ThongBaoXoaLopHP_HK3_2014-2015.pdf" target="_blank">
						3. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 3, 2014-2015.</a></li>
														
					<li><a href="http://gs.ctu.edu.vn/?p=2020" target="_blank">
						4. Thông báo về việc xóa các lớp học phần có số lượng học viên đăng ký ít học kỳ 2 năm học 2014-2015 (Khoa Sau đại học).</a></li>					
					<li><a href="file/ThongBaoXoaLopHP_HK2_2014-2015.pdf" target="_blank">
						5. Thông báo xóa các lớp-học phần có sĩ số không đủ mở lớp học kỳ 2, 2014-2015.</a></li>
					<li><a href="file/dsxoahp_HK2_2014-2015.xls" target="_blank">	
						6. Danh sách sinh viên xóa lớp học phần do không đủ sĩ số mở lớp theo quy định (Theo công văn số:2431 /ĐHCT-ĐT ngày 22/12/2014).</a></li>					
					<li><a href="http://gs.ctu.edu.vn/?p=1720" target="_blank">
						7. Kế hoạch giảng dạy và đăng ký học phần, học kỳ 2, 2014-2015 (Khoa Sau đại học). </a></li>					
						<li><a href="file/SVK40DuocHoanTraHocPhi_HK1_2014_2015.pdf" target="_blank">
						13. Danh sách sinh viên khóa 40 được hoàn trả học phí, học kỳ 1, 2014-2015. </a></li>
					<li><a href="file/CV_HuongDanMienHocPhanKhoa_40.pdf" target="_blank">
						14. C/V Hướng dẫn sinh viên khóa 40 có nhu cầu xét miễn và công nhận điểm hoặc rút học phần học kỳ 1, 2014-2015. </a></li>
						<li><a href="file/Mau Don (mien, cong nhan diem, rut hoc phan).doc" target="_blank">
						15. Mẫu đơn đề nghị xét miễn và công nhận điểm hoặc rút học phần. </a></li>
						<li><a href="file/TBDieuChinhKHGDNgay_01_01_2015.pdf" target="_blank">
						5. Thông báo điều chỉnh kế hoạch giảng dạy, học tập học kỳ 2, 2014-2015 ngày Tết Dương Lịch 01/01/2015. </a> </li>
					<li>6. Theo kế hoạch đã thông báo, thời gian đăng ký học phần đợt 2 học kỳ 2, 2014-2015 sẽ bắt đầu từ ngày 29/12/2014 đến 04/01/2015. Tuy nhiên, do hệ thống quản lý có một thời gian đáp ứng không tốt, trường sẽ tăng thời gian đăng ký đợt 2 thêm 01 tuần, như vậy đợt 2 sẽ kết thúc vào ngày 11/01/2015.</li>
						<li><a href="file/CV_Thong bao dua don sinh vien hoc GDQP_Dot 1_HK2_2014-2015.pdf" target="_blank">
						9. Thông báo đưa đón sinh viên học GDQP đợt 1, HK 2, năm học 2014-2015. </a></li>					
                       <li><a href="Tfile/hongBao_DieuChinhPhongHocNhaDieuHanh.pdf" target="_blank"> 
						4.Điều chỉnh phòng học Học kỳ 2, năm học 2013-2014. Do việc thi công công trình tòa nhà điều hành sau đại học chưa hoàn tất, nên kế hoạch các phòng học có ký hiệu xxxANDH và xxxBNDH có trong thời khóa biểu đã công bố sẽ được điều chỉnh như sau:</a>
						<a href="file/DieuChinhPhongHocNhaDieuHanh_DS.pdf" target="_blank"><b>(Danh sách các lớp Đại học)</b></a>
						<a href="file/DieuChinhPhongHocNhaDieuHanh_DS_SDH.pdf" target="_blank"><b>(Danh sách các lớp Sau đại học)</b></a></li>                        
						-->					
											
                    </ul>
                </td>
            </tr>
        </table>
       </div>
       <div id="page-footer">
                   <div id="footer">
                <p class="top">Trường Đại học Cần Thơ (Can Tho University)</p>
                <p>Khu II, đường 3/2, P. Xuân Khánh, Q. Ninh Kiều, TP. Cần Thơ.</p>
                <p class="bottom">Điện thoại: (84-292) 3832663 - (84-292) 3838474; Fax: (84-292) 3838474; Email: dhct@ctu.edu.vn.</p>
            </td>
        </div>       </div>
    </div>
    </body>
</html>
<script>
$(document).ready(function(){
    window.addEventListener("load", function(event) {
        var url = "capcha/securimage_show.php?sid="+Math.random();
        setTimeout(function(){
            $("#verify_code").attr('src',url);
        },100);
    });
});
</script>