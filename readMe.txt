Site Link To visulaise where each section is:
https://webster2316.github.io/SSA_Training_Bulletin/

##Template for bulletin - INSTRUCTIONS

METHOD ONE:
-Create new file and name it by the week. keep the format YYYY-MM_DD-MM_DD.html
-copy paste everything in Index.html into the new file. 
Items details can easily be edited in outlook so no need to work on that.
-Based on the number of items desired for the bulletin, copy paste/Delete the item SECTION accordingly. 
This is to have editable fields and preserve styling. Outlook does not support copying/creating sections in its local editor.
-Save(Commit changes)

OUTLOOK:
-copy the full code and go to outlook
-If not installed, add the outlook add-in: Insert HTML by Designmodo
-Opens up the add-in and paste your code
You can edit item details here

Ctrl F to find template:  
   <!-- ── COURSE ROW ── -->
..
   <!-- ── END COURSE ROW ── -->
Copy this chunk of code and paste it for however many items are needed beforing moving to outlook.

METHOD TWO:
Copy paste index.html as is and paste it into outlook following the same outlook steps as above.
create a new row under the very last item desc row. 
paste the following using the Insert HTML by Designmodo add-in:

  <!-- ── COURSE ROW ── -->
      <tr>
        <td style="border-bottom:1px solid #e2e8f0;">
 
          <table width="100%" cellpadding="0" cellspacing="0" border="0">
            <tr>
              <td style="padding:16px 24px 10px;">
                <p style="margin:0 0 8px;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:14px;font-weight:700;color:#1a1464;line-height:1.3;">Training Name</p>
                <span style="display:inline-block;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:10px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;padding:3px 10px;border-radius:3px;background:#eef6fb;color:#185fa5;border:1px solid #b5d4f4;">Confirmed</span>
                &nbsp;•&nbsp;
                <span style="display:inline-block;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:10px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;padding:3px 10px;border-radius:3px;background:#f7f9fc;color:#5f6a7d;border:1px solid #dde4ec;">Online</span>
              </td>
            </tr>
          </table>
 
          <table width="100%" cellpadding="0" cellspacing="0" border="0" style="border-top:1px solid #e2e8f0;border-bottom:1px solid #e2e8f0;">
            <tr>
              <td width="25%" style="padding:10px 16px;border-right:1px solid #e2e8f0;vertical-align:top;">
                <p style="margin:0 0 4px;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:9px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#4db8c8;">Date</p>
                <p style="margin:0;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:13px;font-weight:700;color:#1a1464;">Timeframe / Date(s)</p>
              </td>
              <td width="25%" style="padding:10px 16px;border-right:1px solid #e2e8f0;vertical-align:top;">
                <p style="margin:0 0 4px;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:9px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#4db8c8;">Time</p>
                <p style="margin:0;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:13px;font-weight:700;color:#1a1464;">??</p>
              </td>
              <td width="25%" style="padding:10px 16px;border-right:1px solid #e2e8f0;vertical-align:top;">
                <p style="margin:0 0 4px;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:9px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#4db8c8;">Fee (w/ GST)</p>
                <p style="margin:0;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:13px;font-weight:700;color:#1a1464;">S$??</p>
              </td>
              <td width="25%" style="padding:10px 16px;vertical-align:top;">
                <p style="margin:0 0 4px;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:9px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#4db8c8;">Venue</p>
                <p style="margin:0;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:13px;font-weight:700;color:#1a1464;">????</p>
              </td>
            </tr>
          </table>
 
          <table width="100%" cellpadding="0" cellspacing="0" border="0">
            <tr>
              <td style="padding:10px 24px 14px;font-family:'Yu Gothic UI','Yu Gothic','Meiryo','Segoe UI',sans-serif;font-size:13px;color:#4a5568;line-height:1.7;">
                Description if needed.
              </td>
            </tr>
          </table>
 
        </td>
      </tr>
      <!-- ── END COURSE ROW ── -->

Repeat this for as many items needed.
