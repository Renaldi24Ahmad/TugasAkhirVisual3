object Form3: TForm3
  Left = 190
  Top = 183
  Width = 537
  Height = 391
  Caption = 'DAFTAR'
  Color = clGrayText
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'Tahoma'
  Font.Style = []
  OldCreateOrder = False
  PixelsPerInch = 96
  TextHeight = 13
  object Label4l2: TLabel
    Left = 37
    Top = 149
    Width = 85
    Height = 18
    Caption = 'USERNAME'
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -15
    Font.Name = 'Tahoma'
    Font.Style = [fsBold, fsItalic]
    ParentFont = False
  end
  object Label4l3: TLabel
    Left = 37
    Top = 184
    Width = 79
    Height = 18
    Caption = 'PASWORD'
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -15
    Font.Name = 'Tahoma'
    Font.Style = [fsBold, fsItalic]
    ParentFont = False
  end
  object Label1: TLabel
    Left = 200
    Top = 48
    Width = 135
    Height = 23
    Caption = 'DAFTAR USER'
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -19
    Font.Name = 'Tahoma'
    Font.Style = [fsBold, fsItalic]
    ParentFont = False
  end
  object Label3: TLabel
    Left = 37
    Top = 112
    Width = 59
    Height = 18
    Caption = 'STATUS'
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -15
    Font.Name = 'Tahoma'
    Font.Style = [fsBold, fsItalic]
    ParentFont = False
  end
  object Edit1: TEdit
    Left = 153
    Top = 149
    Width = 271
    Height = 21
    TabOrder = 0
  end
  object Edit2: TEdit
    Left = 153
    Top = 184
    Width = 271
    Height = 21
    TabOrder = 1
  end
  object b1: TButton
    Left = 144
    Top = 261
    Width = 97
    Height = 44
    Caption = 'DAFTAR'
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -16
    Font.Name = 'Tahoma'
    Font.Style = [fsBold, fsItalic]
    ParentFont = False
    TabOrder = 2
    OnClick = b1Click
  end
  object b2: TButton
    Left = 264
    Top = 261
    Width = 97
    Height = 44
    Caption = 'LOGIN'
    Font.Charset = DEFAULT_CHARSET
    Font.Color = clWindowText
    Font.Height = -16
    Font.Name = 'Tahoma'
    Font.Style = [fsBold, fsItalic]
    ParentFont = False
    TabOrder = 3
    OnClick = b2Click
  end
  object cmb1: TComboBox
    Left = 152
    Top = 112
    Width = 273
    Height = 21
    ItemHeight = 13
    TabOrder = 4
    Items.Strings = (
      'admin'
      'karyawan'
      'kepala toko')
  end
  object con1: TZConnection
    ControlsCodePage = cGET_ACP
    UTF8StringsAsWideField = False
    AutoEncodeStrings = False
    Connected = True
    HostName = 'localhost'
    Port = 3306
    Database = 'toko_kebab'
    User = 'root'
    Protocol = 'mysql'
    LibraryLocation = 'D:\Rnldi-PC\S4\toko_kebab\libmysql.dll'
    Left = 376
    Top = 256
  end
  object zqry1: TZQuery
    Connection = con1
    Active = True
    SQL.Strings = (
      'SELECT * FROM user')
    Params = <>
    Left = 416
    Top = 256
  end
  object ds1: TDataSource
    DataSet = zqry1
    Left = 456
    Top = 256
  end
end
