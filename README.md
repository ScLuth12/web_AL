# web_AL
Untuk menyimpan file web

if(TxtUser.getText().equals("")){
            JOptionPane.showMessageDialog(null,"Masukan User name");
            TxtUser.requestFocus();
        }
        if(TxtPw.getText().equals("")){
            JOptionPane.showMessageDialog(null,"Masukan Password");
            TxtPw.requestFocus();
        }
        else if(TxtUser.getText().contains("Admin")&& TxtPw.getText().contains("123")){
            new HalamanUtama().show();
            //this.dispose();
        }
        
