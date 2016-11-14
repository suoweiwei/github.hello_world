# github.hello_world
package com.qbao.vc.exception.bless;

import com.qbao.vc.enumeration.ExceptionEnum;
import com.qbao.vc.exception.BusinessException;

/**
 * FrecuencyFeeException
 *
 * @author yinxiang
 * @date 2016/7/28
 */
public class AlertChoiceException extends BusinessException {

    public AlertChoiceException(int code, String message) {
        this.code=code;
        this.message=message;
    }

    public AlertChoiceException(ExceptionEnum e){
        this.code=e.code;
        this.message=e.msg;
    }
}

