# tFPDF
The original code is available at http://fpdf.org/en/script/script92.php<br>
This class is a modified version of FPDF that adds UTF-8 support with additional functions.<br><br>
Arial and Times New Roman True Type fonts were added to "unifont" folder.<br>
You can add more fonts, True Type only.<br>
$pdf->AddFont('arial','','arial.ttf',true);<br>
$pdf->AddFont('times','','times.ttf',true);<br><br>
Additional funczions:<br>
GetMultiCellHeight (border, fill variable not needed<br>
$pdf->GetMultiCellHeight($w, $h, $txt, $align)<br><br>
MultiCellWithOffset(offset cell left/right)<br>
MultiCellWithOffset($w, $h, $txt, $border, $align, $loffset, $roffset, $fill)<br><br>
CellWithPadding(padding left/right)<br>
CellWithPadding($w, $h, $txt, $border, $ln, $align, $lpadding, $rpadding, $fill, $link)<br><br>
