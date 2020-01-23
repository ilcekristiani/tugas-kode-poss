unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TForm1 = class(TForm)
    Label1: TLabel;
    Edit1: TEdit;
    Label3: TLabel;
    Button1: TButton;
    Label2: TLabel;
    Label4: TLabel;
    Label5: TLabel;
    Label6: TLabel;
    Label7: TLabel;
    Label8: TLabel;
    Label9: TLabel;
    procedure Button1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
var nmKota:string;
begin
nmKota:=Edit1.Text;
if ((nmKota = 'PADANG') or (nmKota = 'padang')) then begin
showMessage('PADANG, Kodepos 25000'); end else if ((nmKota='BANDUNG')or(nmKota='bandung')) then begin
showmessage('BANDUNG, Kodepos 40100') end else if ((nmKota='solo')or(nmKota='SOLO')) then begin
showmessage('SOLO, Kodepos 51000') end else if ((nmKota='denpasar')or(nmKota='DENPASAR')) then begin
showmessage('DENPASAR, Kodepos 72000') end else if ((nmKota='palu')or(nmKota='PALU')) then begin
showmessage('PALU, Kodepos 92300')end else showmessage('tidak ditemukan');
end;

end.
